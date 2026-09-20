<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkevy7b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vkevy7b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms" /></template>
