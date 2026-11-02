<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxhhl3etn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxhhl3etn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-line" /></template>
