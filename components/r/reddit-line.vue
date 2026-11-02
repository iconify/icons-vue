<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcfquw3sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcfquw3sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:reddit-line" /></template>
