<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym0uqj59a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ym0uqj59a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pdf-document" /></template>
