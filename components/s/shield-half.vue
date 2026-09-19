<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5fiz9wbv.css';
import '../../css/i/i2gtjkbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w5fiz9wbv"/><path class="i2gtjkbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shield-half" /></template>
