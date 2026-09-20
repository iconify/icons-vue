<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd58tpebb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd58tpebb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shopping-basket" /></template>
