<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yypmncbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yypmncbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rectangle-tall-beside-waters" /></template>
