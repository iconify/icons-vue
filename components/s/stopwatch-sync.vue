<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tafbgqbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tafbgqbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stopwatch-sync" /></template>
