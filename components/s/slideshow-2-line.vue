<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caxky9bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caxky9bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slideshow-2-line" /></template>
