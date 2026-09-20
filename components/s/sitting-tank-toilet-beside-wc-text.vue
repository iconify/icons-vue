<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfwbx1x2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jfwbx1x2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sitting-tank-toilet-beside-wc-text" /></template>
