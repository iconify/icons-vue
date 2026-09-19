<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr0f60m5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0f60m5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:voron" /></template>
