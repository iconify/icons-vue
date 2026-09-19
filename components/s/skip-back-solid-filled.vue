<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xicmvlq6m.css';
import '../../css/x/xh_evphpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xicmvlq6m"/><path class="xh_evphpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skip-back-solid-filled" /></template>
