<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htrmdw6ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="htrmdw6ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rolled-curb-with-exclamation-point" /></template>
