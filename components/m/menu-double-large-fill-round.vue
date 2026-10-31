<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2xtnil3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2xtnil3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-double-large-fill-round" /></template>
