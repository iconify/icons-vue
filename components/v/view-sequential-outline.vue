<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqpbmmucb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqpbmmucb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-sequential-outline" /></template>
