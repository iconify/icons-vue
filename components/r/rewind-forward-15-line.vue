<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e96qdrb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e96qdrb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-15-line" /></template>
