<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drvbacc4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="drvbacc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stripe-s" /></template>
