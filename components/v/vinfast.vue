<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsx9s6fap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zsx9s6fap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vinfast" /></template>
