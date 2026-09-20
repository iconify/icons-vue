<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swi7bqb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swi7bqb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:server-2-line" /></template>
