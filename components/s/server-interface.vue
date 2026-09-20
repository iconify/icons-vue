<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox6q4zbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ox6q4zbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:server-interface" /></template>
