<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo28wy1dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo28wy1dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shadow-solid" /></template>
