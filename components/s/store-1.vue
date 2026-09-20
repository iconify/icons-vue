<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx9ebdb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qx9ebdb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:store-1" /></template>
