<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6zmekbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6zmekbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nfc-line" /></template>
