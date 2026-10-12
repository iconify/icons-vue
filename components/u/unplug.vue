<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctpwtsw7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unplug" /></template>
<style>
.ctpwtsw7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.1854 13.0433L10.9567 16.8146C11.7377 17.5956 11.7378 18.8619 10.9567 19.643L10.4853 20.1144C8.6629 21.9369 5.7081 21.9368 3.8856 20.1144C2.0632 18.2919 2.0631 15.3371 3.8856 13.5147L4.357 13.0433C5.1381 12.2622 6.4044 12.2623 7.1854 13.0433ZM16.8146 10.9567L13.0433 7.1854C12.2623 6.4044 12.2622 5.1381 13.0433 4.357L13.5147 3.8856C15.3371 2.0631 18.2919 2.0632 20.1144 3.8856C21.9368 5.7081 21.9369 8.6629 20.1144 10.4853L19.643 10.9567C18.8619 11.7378 17.5956 11.7377 16.8146 10.9567ZM7.6569 13.5147L10.0139 11.1577M10.4853 16.3431L12.8423 13.9861M3.8856 20.1144L2 22M20.1144 3.8856L22 2");
}

</style>
