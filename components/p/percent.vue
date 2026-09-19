<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyozl1h3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":819};
const content = `<path class="yyozl1h3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:percent" /></template>
