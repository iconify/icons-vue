<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4xm99bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t4xm99bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:medication" /></template>
