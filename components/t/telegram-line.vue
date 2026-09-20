<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdlu0hf_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdlu0hf_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:telegram-line" /></template>
