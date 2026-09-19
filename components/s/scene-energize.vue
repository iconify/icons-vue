<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajnm_s8pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajnm_s8pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scene-energize" /></template>
