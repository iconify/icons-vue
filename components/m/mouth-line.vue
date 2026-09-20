<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myw63ybnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myw63ybnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mouth-line" /></template>
