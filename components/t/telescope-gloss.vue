<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhoe5vyjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhoe5vyjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:telescope-gloss" /></template>
