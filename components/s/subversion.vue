<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn1qgzb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vn1qgzb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:subversion" /></template>
