<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzopzdowi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzopzdowi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-transfer-horizontal-bold" /></template>
