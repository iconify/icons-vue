<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu5xhwzcj.css';
import '../../css/y/ywttjwgha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xu5xhwzcj"/><path class="ywttjwgha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:screen-arrow-up-fill-20" /></template>
