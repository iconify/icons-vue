<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-y3f3b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x-y3f3b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:python-logo-blue" /></template>
