<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbvf0ch1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbvf0ch1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vector-off" /></template>
