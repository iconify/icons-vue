<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqh0-kb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqh0-kb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-line" /></template>
