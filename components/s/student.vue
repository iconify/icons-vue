<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp6ggp7mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp6ggp7mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:student" /></template>
