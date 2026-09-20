<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pffvj1x9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pffvj1x9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:share-outlined" /></template>
