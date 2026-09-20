<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca4h09bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ca4h09bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:semi-trailer" /></template>
