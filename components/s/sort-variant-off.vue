<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnn2f8bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnn2f8bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-variant-off" /></template>
