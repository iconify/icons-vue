<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz8plk1ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz8plk1ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:share-forward-line" /></template>
