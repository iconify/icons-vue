<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm_t_cc9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zm_t_cc9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:not-equal-sign" /></template>
