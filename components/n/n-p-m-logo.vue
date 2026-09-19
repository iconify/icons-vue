<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_r730eqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="y_r730eqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:n-p-m-logo" /></template>
