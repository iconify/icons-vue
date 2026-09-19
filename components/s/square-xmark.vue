<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf_7ibbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mf_7ibbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:square-xmark" /></template>
