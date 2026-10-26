<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":258};
const content = `<path class="rg155fb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:rudderstack-icon" /></template>
<style>
.rg155fb3o {
  d: path("M256 0H0c0 136.177 106.017 248.816 241.945 257.057l14.055.852z");
}

</style>
