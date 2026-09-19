<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq1fj96eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mq1fj96eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oil-can" /></template>
