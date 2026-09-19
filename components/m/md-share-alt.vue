<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvo81jd5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pvo81jd5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-share-alt" /></template>
