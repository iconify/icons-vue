<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs6y6ggvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fs6y6ggvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:xsplit" /></template>
