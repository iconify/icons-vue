<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7pj_5bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":741};
const content = `<path class="x7pj_5bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:speed" /></template>
