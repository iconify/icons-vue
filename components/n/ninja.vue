<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af99qwqhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="af99qwqhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ninja" /></template>
