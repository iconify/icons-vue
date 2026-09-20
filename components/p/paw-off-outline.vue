<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp00hucjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp00hucjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paw-off-outline" /></template>
