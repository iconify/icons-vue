<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-rb9-z-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-1-sharp" /></template>
<style>
.t-rb9-z-f {
  fill: currentColor;
  d: path("M12.77 18.116v-11H9V5.885h5v12.23z");
}

</style>
