<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnw8g3zvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnw8g3zvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pray-line" /></template>
