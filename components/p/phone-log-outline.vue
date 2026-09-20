<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp7d7ipnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp7d7ipnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-log-outline" /></template>
