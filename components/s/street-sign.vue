<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn3l1bc2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rn3l1bc2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:street-sign" /></template>
