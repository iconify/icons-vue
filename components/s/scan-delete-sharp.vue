<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcxihvbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scan-delete-sharp" /></template>
<style>
.vcxihvbmf {
  fill: currentColor;
  d: path("M14 8h4l-4-4zm1.9 12.866l-.688-.689l2.1-2.1l-2.1-2.1l.688-.689l2.1 2.1l2.1-2.1l.689.689l-2.075 2.1l2.075 2.1l-.689.689L18 18.79zM5 21V3h9.5L19 7.5v4.812q-.238-.06-.488-.09t-.512-.03q-2.452 0-4.168 1.704t-1.717 4.156q0 .74.208 1.528q.208.787.63 1.42z");
}

</style>
