<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy360kq_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-guest-24-filled" /></template>
<style>
.hy360kq_m {
  fill: currentColor;
  d: path("M20.5 12a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-4a2.5 2.5 0 0 1-2.5-2.5v-6a2.5 2.5 0 0 1 2.5-2.5zm-7.464 2q-.035.245-.036.5v6c0 .393.065.77.185 1.122q-1.434.377-3.185.379c-3.42 0-5.943-1.072-7.485-3.236a2.75 2.75 0 0 1-.511-1.596v-.92A2.25 2.25 0 0 1 4.253 14zM17 14a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM10 2.005a5 5 0 1 1 0 10a5 5 0 0 1 0-10");
}

</style>
