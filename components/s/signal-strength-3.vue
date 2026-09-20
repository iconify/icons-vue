<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuczdyokf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xuczdyokf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:signal-strength-3" /></template>
