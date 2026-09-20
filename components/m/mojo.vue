<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbg5zkbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qbg5zkbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:mojo" /></template>
