<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0-ge9aao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v0-ge9aao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:sandbox" /></template>
