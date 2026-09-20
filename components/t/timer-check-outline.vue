<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v2rqs8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9v2rqs8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-check-outline" /></template>
