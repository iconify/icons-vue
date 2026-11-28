<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-o4xzb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-o4xzb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video" /></template>
