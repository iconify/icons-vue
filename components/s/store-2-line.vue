<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbhcn1b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbhcn1b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:store-2-line" /></template>
