<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0b83e9ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0b83e9ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-in-talk-outline" /></template>
