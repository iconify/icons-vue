<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozvh-ybic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozvh-ybic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wiim-alt" /></template>
