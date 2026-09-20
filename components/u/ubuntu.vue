<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj_uz2bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gj_uz2bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ubuntu" /></template>
