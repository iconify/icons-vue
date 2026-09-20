<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbdst0b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbdst0b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pyramid-off" /></template>
