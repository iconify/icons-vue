<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq-njj5ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wq-njj5ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-left-with-plus" /></template>
