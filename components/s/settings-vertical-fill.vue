<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf5r8qbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf5r8qbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-vertical-fill" /></template>
