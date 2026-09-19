<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzv9pj7uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzv9pj7uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:slideshow" /></template>
