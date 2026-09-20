<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyls0t1sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyls0t1sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rotate-to-vertical-line" /></template>
