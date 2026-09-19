<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh7ab-y9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":472};
const content = `<path class="sh7ab-y9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:power-setting" /></template>
