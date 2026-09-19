<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew3fm4blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ew3fm4blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:tencent-qq" /></template>
