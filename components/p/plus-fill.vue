<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvhyp-cmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvhyp-cmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:plus-fill" /></template>
