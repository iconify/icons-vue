<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kznf9zb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kznf9zb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:utorrent" /></template>
