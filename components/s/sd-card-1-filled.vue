<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuwblnb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuwblnb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sd-card-1-filled" /></template>
