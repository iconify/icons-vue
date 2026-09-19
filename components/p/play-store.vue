<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am38jwbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am38jwbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:play-store" /></template>
