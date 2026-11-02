<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5qow_bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5qow_bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wechat-miniprogram-line" /></template>
