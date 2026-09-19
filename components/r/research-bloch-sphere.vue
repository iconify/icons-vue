<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtsz_ig2m.css';
import '../../css/c/cgvv3fb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qtsz_ig2m"/><path class="cgvv3fb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:research-bloch-sphere" /></template>
