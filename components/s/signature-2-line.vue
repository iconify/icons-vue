<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slnehab3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slnehab3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:signature-2-line" /></template>
