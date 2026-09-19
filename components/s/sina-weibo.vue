<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8za_lbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="n8za_lbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sina-weibo" /></template>
