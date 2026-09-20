<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5jatfe6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:system-update-outline-sharp" /></template>
<style>
.c5jatfe6w {
  fill: currentColor;
  d: path("M12 15.308L15.308 12l-.708-.708l-2.1 2.089V8.692h-1v4.689l-2.1-2.089l-.708.708zM6 22V2h12.077v4.83H19v3.686h-.923V22zm1-1h10.077V3H7zm0 0V3z");
}

</style>
