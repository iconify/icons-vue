<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6kkeeboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:metronome-app" /></template>
<style>
.a6kkeeboi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.875 1.75h4.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-4.25q-2.123 0-3.624-1.501T4.75 17.125V6.875q0-2.123 1.501-3.624T9.875 1.75M8.581 18.433q.675.817 1.735.817h3.368q1.06 0 1.735-.817q.674-.817.475-1.858l-.998-5.189l1.275-2.551q.067-.133.077-.282q.011-.149-.036-.29q-.048-.142-.145-.254q-.098-.113-.232-.18q-.066-.033-.137-.052q-.071-.02-.145-.025t-.147.004t-.143.032q-.07.024-.134.06q-.065.037-.12.085q-.056.049-.101.107q-.046.059-.079.125l-.399.798l-.504-2.623Q13.619 4.75 12 4.75t-1.925 1.59L8.106 16.575q-.199 1.041.475 1.858");
}

</style>
