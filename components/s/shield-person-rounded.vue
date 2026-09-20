<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hit46hbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-person-rounded" /></template>
<style>
.hit46hbwi {
  fill: currentColor;
  d: path("M14.129 11.629Q15 10.758 15 9.5t-.871-2.129T12 6.5t-2.129.871T9 9.5t.871 2.129T12 12.5t2.129-.871M12 19.9q1.34-.436 2.43-1.305q1.09-.868 1.882-2.028q-.999-.511-2.084-.789Q13.142 15.5 12 15.5t-2.228.278t-2.084.79q.793 1.159 1.882 2.027q1.09.869 2.43 1.305m-.287.917q-.15-.025-.28-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025");
}

</style>
