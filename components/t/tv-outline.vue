<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyok70tso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyok70tso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:tv-outline" /></template>
