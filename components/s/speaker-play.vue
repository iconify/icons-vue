<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzl4o-zjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzl4o-zjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speaker-play" /></template>
