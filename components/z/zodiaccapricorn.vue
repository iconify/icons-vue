<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haqop-b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="haqop-b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zodiaccapricorn" /></template>
