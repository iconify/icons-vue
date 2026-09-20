<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va6l_eb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va6l_eb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:steam-line" /></template>
