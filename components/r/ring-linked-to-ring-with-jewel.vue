<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwke6u-sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vwke6u-sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ring-linked-to-ring-with-jewel" /></template>
