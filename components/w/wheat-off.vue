<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxxbe6b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxxbe6b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wheat-off" /></template>
