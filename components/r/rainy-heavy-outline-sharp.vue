<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvl7kbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rainy-heavy-outline-sharp" /></template>
<style>
.jtvl7kbup {
  fill: currentColor;
  d: path("M7.55 19.35L.65 5.55l1.8-.875l6.9 13.75zm4.675 0l-6.9-13.8l1.8-.9L14 18.425zm4.675 0L10 5.55l1.775-.9l6.9 13.775zm4.65-.025L14.675 5.55l1.775-.9l6.9 13.8z");
}

</style>
