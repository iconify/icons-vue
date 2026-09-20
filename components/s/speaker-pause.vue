<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkkd93b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkkd93b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speaker-pause" /></template>
