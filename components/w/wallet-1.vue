<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgi0tgbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="pgi0tgbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wallet-1" /></template>
