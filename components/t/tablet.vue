<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko01m9x0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko01m9x0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tablet" /></template>
