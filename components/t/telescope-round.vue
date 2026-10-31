<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qblsphrvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qblsphrvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telescope-round" /></template>
