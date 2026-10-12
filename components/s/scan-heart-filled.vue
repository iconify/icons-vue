<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytrgcm7bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytrgcm7bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-heart-filled" /></template>
