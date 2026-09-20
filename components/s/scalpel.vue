<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_f_r3bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="v_f_r3bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:scalpel" /></template>
