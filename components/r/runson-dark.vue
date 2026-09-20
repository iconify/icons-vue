<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmnnnw1xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmnnnw1xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:runson-dark" /></template>
