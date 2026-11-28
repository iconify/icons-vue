<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm-6fxb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm-6fxb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:meeting-check" /></template>
