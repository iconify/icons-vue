<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ngav9e32t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stack-vertical-28-filled" /></template>
<style>
.ngav9e32t {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75V24a1 1 0 1 1-2 0v-5.25A1.75 1.75 0 0 0 21.25 17H6.75A1.75 1.75 0 0 0 5 18.75V24a1 1 0 1 1-2 0V6.75A3.75 3.75 0 0 1 6.75 3zm-14.5 8A1.75 1.75 0 0 0 5 12.75v2.683A3.7 3.7 0 0 1 6.75 15h14.5c.632 0 1.228.156 1.75.433V12.75A1.75 1.75 0 0 0 21.25 11zm0-6A1.75 1.75 0 0 0 5 6.75v2.683A3.7 3.7 0 0 1 6.75 9h14.5c.632 0 1.228.156 1.75.433V6.75A1.75 1.75 0 0 0 21.25 5z");
}

</style>
