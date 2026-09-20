<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s62efnbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s62efnbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trend-sideways-filled" /></template>
