<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwdw506lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mwdw506lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:mountain-range" /></template>
