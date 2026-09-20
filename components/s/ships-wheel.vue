<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdkr5jbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wdkr5jbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ships-wheel" /></template>
