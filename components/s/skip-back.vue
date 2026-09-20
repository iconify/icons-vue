<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_mkzf7xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_mkzf7xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:skip-back" /></template>
