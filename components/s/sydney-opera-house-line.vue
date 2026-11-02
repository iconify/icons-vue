<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd2sngqei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd2sngqei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sydney-opera-house-line" /></template>
