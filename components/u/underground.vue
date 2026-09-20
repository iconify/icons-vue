<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p74fnccdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p74fnccdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:underground" /></template>
