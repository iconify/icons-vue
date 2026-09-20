<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb95u1bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb95u1bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sawtooth-wave" /></template>
