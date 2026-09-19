<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6riqxspa.css';
import '../../css/o/o2503rbla.css';
import '../../css/y/yti26qboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="v6riqxspa"/><path class="o2503rbla"/><path class="yti26qboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unknown" /></template>
