<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cscje9bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cscje9bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-zap-solid" /></template>
