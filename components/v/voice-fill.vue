<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri4xrpbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri4xrpbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:voice-fill" /></template>
