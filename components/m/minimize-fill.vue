<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdo1-lb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdo1-lb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:minimize-fill" /></template>
