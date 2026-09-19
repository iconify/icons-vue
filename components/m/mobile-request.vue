<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbrtgmd9d.css';
import '../../css/i/iuvb3zcak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kbrtgmd9d"/><path class="iuvb3zcak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-request" /></template>
