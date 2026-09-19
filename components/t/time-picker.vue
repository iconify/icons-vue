<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re_271bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="re_271bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:time-picker" /></template>
