<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elqse40db.css';
import '../../css/h/hkk3_ybhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="elqse40db"/><path class="hkk3_ybhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-filled" /></template>
