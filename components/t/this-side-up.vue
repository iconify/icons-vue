<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2_t1hbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_t1hbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:this-side-up" /></template>
