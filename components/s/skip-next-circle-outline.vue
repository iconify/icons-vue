<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/calg-m4sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="calg-m4sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-next-circle-outline" /></template>
