<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blh-xxc1n.css';
import '../../css/m/m3q-h-bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="blh-xxc1n"/><path class="m3q-h-bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:microphone" /></template>
