<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6lfvib6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c6lfvib6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:pen" /></template>
