<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ahpsbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ahpsbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pinboard" /></template>
