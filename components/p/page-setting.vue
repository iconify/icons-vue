<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_e3mtb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="y_e3mtb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:page-setting" /></template>
