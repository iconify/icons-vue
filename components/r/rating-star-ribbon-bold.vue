<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geymjob6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geymjob6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:rating-star-ribbon-bold" /></template>
