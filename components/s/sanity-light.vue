<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yybedubjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":192};
const content = `<path class="yybedubjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sanity-light" /></template>
