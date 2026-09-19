<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5gfc9b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5gfc9b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rook" /></template>
