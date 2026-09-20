<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0z3i-1xz.css';
import '../../css/k/kj2p-acws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0z3i-1xz"/><path class="kj2p-acws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:questionnaire-double-filled" /></template>
