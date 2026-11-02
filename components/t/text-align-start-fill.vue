<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u67sr_bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u67sr_bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-align-start-fill" /></template>
