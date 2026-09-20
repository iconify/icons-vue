<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmpbfdbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmpbfdbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:t-shirt-fill" /></template>
