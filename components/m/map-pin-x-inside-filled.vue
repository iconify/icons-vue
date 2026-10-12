<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1j12acbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1j12acbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-x-inside-filled" /></template>
