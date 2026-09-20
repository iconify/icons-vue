<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa8todb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa8todb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:navigation-outline" /></template>
