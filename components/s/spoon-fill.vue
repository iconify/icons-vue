<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naf6cbb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="naf6cbb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spoon-fill" /></template>
