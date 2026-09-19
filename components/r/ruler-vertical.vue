<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3mm8r2qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="x3mm8r2qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ruler-vertical" /></template>
