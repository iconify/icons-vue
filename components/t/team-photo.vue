<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmx56drnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:team-photo" /></template>
<style>
.gmx56drnv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 3.25H6.875q-2.123 0-3.624 1.501T1.75 8.375v6.75q0 2.123 1.501 3.624q.47.47 1 .792L4.25 19.5q0-5.75 4.25-5.75q2.602 0 4.135 2.246Q13.862 15 16 15q3.75 0 3.75 4.5l-.001.041q.53-.322 1-.792q1.501-1.501 1.501-3.624v-6.75q0-2.123-1.501-3.624T17.125 3.25m1.39 16.822q-.126-.107-.196-.257q-.069-.15-.069-.315q0-3-2.25-3q-2.099 0-2.876 1.166q-.11.166-.289.255q-.133.067-.282.077q-.149.011-.29-.036q-.142-.048-.254-.145q-.113-.098-.18-.232Q10.661 15.25 8.5 15.25q-2.75 0-2.75 4.25q0 .165-.069.315q-.07.15-.196.257q.658.178 1.39.178h10.25q.732 0 1.39-.178M5.25 9q0-3.25 3.25-3.25T11.75 9T8.5 12.25T5.25 9M16 8.25q2.75 0 2.75 2.75T16 13.75T13.25 11T16 8.25");
}

</style>
