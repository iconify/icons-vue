<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkj7i78ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zkj7i78ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:shinto" /></template>
