<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hke452bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hke452bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:satellite" /></template>
