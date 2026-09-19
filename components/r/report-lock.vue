<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anu-u3t_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="anu-u3t_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:report-lock" /></template>
