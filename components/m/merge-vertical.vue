<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x658pnwbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x658pnwbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:merge-vertical" /></template>
