<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb25rsc5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cb25rsc5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:settings" /></template>
