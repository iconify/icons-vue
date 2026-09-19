<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaamibb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uaamibb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:view-list" /></template>
