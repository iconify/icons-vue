<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1roa6qwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-check-sharp" /></template>
<style>
.t1roa6qwm {
  fill: currentColor;
  d: path("m11.05 14.308l4.258-4.258l-.708-.708l-3.55 3.55l-1.4-1.4l-.708.708zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
