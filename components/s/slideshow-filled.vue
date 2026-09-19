<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuyjo_bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuyjo_bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:slideshow-filled" /></template>
