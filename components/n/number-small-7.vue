<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxq749buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vxq749buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-7" /></template>
