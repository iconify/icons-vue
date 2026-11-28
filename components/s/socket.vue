<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i63fjcrdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i63fjcrdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:socket" /></template>
