<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blh-xxc1n.css';
import '../../css/t/t0z_rmbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="blh-xxc1n"/><path class="t0z_rmbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:microphone-filled" /></template>
