<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r93y31_uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r93y31_uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:music-outline" /></template>
