<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpkkw208p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpkkw208p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smile" /></template>
