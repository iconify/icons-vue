<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we4oo-_ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="we4oo-_ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:square" /></template>
