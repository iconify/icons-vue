<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uabn4_hhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uabn4_hhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pig-fill" /></template>
