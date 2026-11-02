<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqwpjbt-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqwpjbt-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-plus-fill" /></template>
