<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqor534jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqor534jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wine-line" /></template>
