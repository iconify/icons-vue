<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltogj7x2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltogj7x2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:to-do-line" /></template>
