<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrvc4db4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrvc4db4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:social-distance-6-feet" /></template>
