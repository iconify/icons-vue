<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_opwzr2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t_opwzr2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rewind" /></template>
