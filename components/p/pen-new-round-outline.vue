<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo_qq2bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uo_qq2bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-new-round-outline" /></template>
