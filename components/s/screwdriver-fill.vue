<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux_szwjre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux_szwjre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:screwdriver-fill" /></template>
