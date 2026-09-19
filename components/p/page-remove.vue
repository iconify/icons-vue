<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qapub4bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qapub4bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:page-remove" /></template>
