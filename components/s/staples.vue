<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ul-wbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":184.201,"height":38.9};
const content = `<path class="g8ul-wbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:staples" /></template>
