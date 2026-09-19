<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ziozb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q3ziozb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:zeit" /></template>
