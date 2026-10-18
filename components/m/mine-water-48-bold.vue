<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-8-n5brx.css';
import '../../css/u/uv7uxpbju.css';
import '../../css/o/odn04e7iv.css';
import '../../css/i/i5hs3-3ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o-8-n5brx"/><path class="uv7uxpbju"/><path class="odn04e7iv"/><path class="i5hs3-3ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-water-48-bold" /></template>
