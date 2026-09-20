<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv94u5byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv94u5byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-security-line" /></template>
