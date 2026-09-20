<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyp91c7tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyp91c7tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:silver-airways" /></template>
