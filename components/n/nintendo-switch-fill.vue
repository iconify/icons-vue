<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbyr-ac6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbyr-ac6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nintendo-switch-fill" /></template>
