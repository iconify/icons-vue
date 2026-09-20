<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyvcpjbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-info-sharp" /></template>
<style>
.vyvcpjbuv {
  fill: currentColor;
  d: path("M11.5 15.962h1v-5h-1zm.934-6.985q.182-.177.182-.438t-.182-.439T12 7.923t-.434.182t-.182.434t.182.433t.434.182t.434-.177M6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
