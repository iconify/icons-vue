<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1t2jvjmb.css';
import '../../css/t/tizvf-b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u1t2jvjmb"/><path class="tizvf-b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:phone-set" /></template>
