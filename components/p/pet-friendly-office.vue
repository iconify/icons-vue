<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j433us6pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-friendly-office" /></template>
<style>
.j433us6pk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 5.75Q6 3 8.75 3t2.75 2.75T8.75 8.5T6 5.75M15.25 3Q12.5 3 12.5 5.75t2.75 2.75T18 5.75T15.25 3M4.5 7.75q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75T4.5 7.75m12.25 2.75q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75t-2.75-2.75M12 11.75q2.465 0 4.413 2.009q1.837 1.894 1.837 3.991q0 1.675-1.248 2.577q-1.225.884-2.728.388q-1.553-.465-2.274-.465t-2.274.465q-1.503.496-2.728-.388q-1.248-.902-1.248-2.577q0-2.097 1.837-3.991Q9.535 11.75 12 11.75");
}

</style>
