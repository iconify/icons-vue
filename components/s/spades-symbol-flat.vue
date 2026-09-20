<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc-_-yb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oc-_-yb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:spades-symbol-flat" /></template>
