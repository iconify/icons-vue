<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxpc2vbsc.css';
import '../../css/p/p575c8b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="dxpc2vbsc"/><path class="p575c8b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:users" /></template>
