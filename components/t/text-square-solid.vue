<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upt_ysqso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="upt_ysqso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:text-square-solid" /></template>
