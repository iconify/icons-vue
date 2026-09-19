<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csi3jmbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="csi3jmbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:spacer" /></template>
