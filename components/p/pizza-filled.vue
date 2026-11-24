<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgooogbsq.css';
import '../../css/d/d0-_7mw1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgooogbsq"/><path class="d0-_7mw1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pizza-filled" /></template>
