<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pby5r5c2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pby5r5c2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-2-line" /></template>
