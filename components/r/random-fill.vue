<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfca5tesk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfca5tesk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:random-fill" /></template>
