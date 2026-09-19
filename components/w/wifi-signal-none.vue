<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td7gww7fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td7gww7fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:wifi-signal-none" /></template>
