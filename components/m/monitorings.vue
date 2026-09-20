<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyz6619jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xyz6619jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:monitorings" /></template>
