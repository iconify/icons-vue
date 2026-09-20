<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xle9labyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xle9labyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:soup-pot-fill" /></template>
