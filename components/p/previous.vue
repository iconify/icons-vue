<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4yel-fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":472};
const content = `<path class="zv4yel-fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:previous" /></template>
