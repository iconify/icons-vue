<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oubyt4bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oubyt4bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:select-arrow-up" /></template>
