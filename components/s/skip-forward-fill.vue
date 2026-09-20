<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmeo3-b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmeo3-b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skip-forward-fill" /></template>
