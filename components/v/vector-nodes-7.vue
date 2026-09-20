<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owo7uxusz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="owo7uxusz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vector-nodes-7" /></template>
