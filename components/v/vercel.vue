<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4i2dwbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4i2dwbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:vercel" /></template>
