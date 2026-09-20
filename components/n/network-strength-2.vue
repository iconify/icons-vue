<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpyr9_ile.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpyr9_ile"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-2" /></template>
