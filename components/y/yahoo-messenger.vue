<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz8xdsbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="mz8xdsbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:yahoo-messenger" /></template>
