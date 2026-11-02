<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwwjsgban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwwjsgban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wineglass-2-fill" /></template>
