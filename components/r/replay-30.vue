<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb7td8ixk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="zb7td8ixk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:replay-30" /></template>
