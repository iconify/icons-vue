<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2ou5voen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ou5voen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:thermostat" /></template>
