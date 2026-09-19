<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lclbo1n2e.css';
import '../../css/h/helnm_mgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lclbo1n2e"/><path class="helnm_mgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:satellite-radar" /></template>
