<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkhcm6b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hkhcm6b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:steak-fill" /></template>
