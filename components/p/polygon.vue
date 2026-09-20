<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbswf2fdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vbswf2fdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:polygon" /></template>
