<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qit8fdbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qit8fdbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:pc-case-sharp" /></template>
