<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xan1sebrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xan1sebrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:promoted-database" /></template>
