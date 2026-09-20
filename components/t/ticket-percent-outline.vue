<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kewrg803m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kewrg803m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ticket-percent-outline" /></template>
