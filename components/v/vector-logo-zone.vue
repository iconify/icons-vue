<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zivi7kbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zivi7kbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vector-logo-zone" /></template>
