<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd6sy5lsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hd6sy5lsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:rectangle-stack" /></template>
