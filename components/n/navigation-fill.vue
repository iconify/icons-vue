<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr7sn_xxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kr7sn_xxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:navigation-fill" /></template>
