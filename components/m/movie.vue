<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wayv_wbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wayv_wbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:movie" /></template>
