<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0kebbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx0kebbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-round" /></template>
