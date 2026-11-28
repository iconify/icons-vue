<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx83zxlsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx83zxlsq primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pipe-duotone" /></template>
