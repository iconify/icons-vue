<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol09ncwdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol09ncwdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-playbase" /></template>
