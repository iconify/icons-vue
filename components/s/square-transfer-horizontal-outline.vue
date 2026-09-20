<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvnkoh0_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvnkoh0_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-transfer-horizontal-outline" /></template>
