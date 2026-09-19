<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pojn_z1wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pojn_z1wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:report-hacked" /></template>
