<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4dtb0bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4dtb0bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-off-line" /></template>
