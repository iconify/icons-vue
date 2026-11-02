<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvnosdbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvnosdbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moai-fill" /></template>
