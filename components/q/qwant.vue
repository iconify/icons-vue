<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr8olibst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr8olibst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qwant" /></template>
