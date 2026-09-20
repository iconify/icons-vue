<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3np6cb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3np6cb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:slint" /></template>
