<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zs84e7jzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tent-12-filled" /></template>
<style>
.zs84e7jzd {
  fill: currentColor;
  d: path("M6.432 1.457a.5.5 0 0 0-.768 0c-.727.873-2.18 1.924-3.017 2.391a.5.5 0 0 0-.252.369l-.658 4.781h-.233a.5.5 0 1 0 0 1h8.993a.5.5 0 1 0 0-1h-.137l-.659-4.781a.5.5 0 0 0-.251-.369c-.837-.467-2.29-1.518-3.018-2.39m-1.599 7.54c.407-.633.818-1.417 1.202-2.505c.354.999.744 1.775 1.206 2.505z");
}

</style>
