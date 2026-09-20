<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssmt6smrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ssmt6smrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sofa-solid" /></template>
