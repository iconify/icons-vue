<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs0c_5blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs0c_5blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-left-bold" /></template>
