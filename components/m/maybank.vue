<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm5r9sbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1568,"height":1568};
const content = `<path class="xm5r9sbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:maybank" /></template>
