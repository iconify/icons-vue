<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-apdlbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-apdlbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-zap-solid" /></template>
