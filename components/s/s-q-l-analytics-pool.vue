<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsfqp5b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vsfqp5b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:s-q-l-analytics-pool" /></template>
