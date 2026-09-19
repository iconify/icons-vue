<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6-hb5m7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6-hb5m7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nexo" /></template>
