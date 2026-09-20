<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxut9fbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uxut9fbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-disabled" /></template>
