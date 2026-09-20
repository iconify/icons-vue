<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql119pv2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ql119pv2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tape" /></template>
