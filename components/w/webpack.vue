<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtm0kz49x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtm0kz49x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:webpack" /></template>
