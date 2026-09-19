<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgphr9pxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="xgphr9pxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:oval" /></template>
