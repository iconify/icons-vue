<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rngmbwozf.css';
import '../../css/o/obx0gf1ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rngmbwozf"/><path class="obx0gf1ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mic" /></template>
