<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfglxw37l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qfglxw37l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:yarn" /></template>
