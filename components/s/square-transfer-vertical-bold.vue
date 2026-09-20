<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiop2sbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jiop2sbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-transfer-vertical-bold" /></template>
