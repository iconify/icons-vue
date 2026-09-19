<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxj4sybpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1026};
const content = `<path class="kxj4sybpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:polygonlasso" /></template>
