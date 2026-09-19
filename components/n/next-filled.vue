<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7806flpi.css';
import '../../css/v/v9la5m20b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o7806flpi"/><path class="v9la5m20b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:next-filled" /></template>
