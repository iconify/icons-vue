<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugg4w_bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ugg4w_bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spinner-arrow" /></template>
