<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkv2i5z9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkv2i5z9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sandglass-2-line" /></template>
