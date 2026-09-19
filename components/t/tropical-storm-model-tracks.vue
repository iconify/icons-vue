<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7ieikbdu.css';
import '../../css/y/ypqutt2oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i7ieikbdu"/><path class="ypqutt2oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tropical-storm-model-tracks" /></template>
