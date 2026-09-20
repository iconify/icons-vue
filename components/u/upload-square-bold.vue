<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzl_0yb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzl_0yb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-square-bold" /></template>
