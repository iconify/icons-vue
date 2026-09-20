<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2cph-6yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n2cph-6yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pc-tower-settings" /></template>
