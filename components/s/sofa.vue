<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdz7ysb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1600};
const content = `<path class="tdz7ysb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sofa" /></template>
