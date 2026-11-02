<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io4e73bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io4e73bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:telescope-fill" /></template>
