<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/han1l8bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="han1l8bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:npm" /></template>
