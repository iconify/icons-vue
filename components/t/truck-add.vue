<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n--itubox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n--itubox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-add" /></template>
