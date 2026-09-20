<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6sla38dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upcoming-sharp" /></template>
<style>
.t6sla38dm {
  fill: currentColor;
  d: path("M2 21v-9h7q0 1.25.875 2.125T12 15t2.125-.875T15 12h7v9zm15.6-10.2l-1.4-1.4l3.55-3.55l1.4 1.4zm-11.2 0L2.85 7.25l1.4-1.4L7.8 9.4zM11 8V3h2v5z");
}

</style>
