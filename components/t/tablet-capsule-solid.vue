<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz5y_9bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zz5y_9bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:tablet-capsule-solid" /></template>
