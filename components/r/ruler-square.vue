<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpvn-kb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpvn-kb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ruler-square" /></template>
