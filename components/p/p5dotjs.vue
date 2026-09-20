<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpce0cc9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpce0cc9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:p5dotjs" /></template>
