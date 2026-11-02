<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl2f5u--n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2f5u--n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sale-line" /></template>
