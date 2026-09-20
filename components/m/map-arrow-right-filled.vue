<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3wlhpvuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3wlhpvuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-arrow-right-filled" /></template>
