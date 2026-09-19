<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3t0tdi0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="c3t0tdi0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:nfc-symbol" /></template>
