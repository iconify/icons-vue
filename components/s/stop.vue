<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae2tqmaki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae2tqmaki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:stop" /></template>
