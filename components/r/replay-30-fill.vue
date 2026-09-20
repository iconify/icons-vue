<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amx09ccet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amx09ccet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:replay-30-fill" /></template>
