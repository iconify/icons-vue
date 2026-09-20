<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi0i5it0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi0i5it0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-fog-fill" /></template>
