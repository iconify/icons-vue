<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1t33f54q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1t33f54q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:slickpic" /></template>
