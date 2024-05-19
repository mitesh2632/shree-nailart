<script setup>
import DefaultReviewCard from "@/examples/cards/reviewCards/DefaultReviewCard.vue";
</script>
<template>
  <section class="py-7">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 mx-auto text-center">
          <h2 class="mb-0">Reviews</h2>
        </div>
      </div>
      <div class="row mt-6">
        <DefaultReviewCard
          name="Asha Patel"
          date="1 day ago"
          review="This is an excellent design, i like their art."
          :rating="5.0"
        />
        <DefaultReviewCard
          class="ms-md-auto"
          color="bg-gradient-success"
          name="Nisha Patel"
          date="1 week ago"
          review="Excellent Work"
          :rating="5.0"
        />

        <DefaultReviewCard
          name="Gita Kansara"
          date="3 weeks ago"
          review="Great
        product."
          :rating="5.0"
        />
      </div>
      <hr class="horizontal dark my-5" />
    </div>
  </section>
</template>
