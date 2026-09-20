<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r94-7wsro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r94-7wsro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:xing-line" /></template>
