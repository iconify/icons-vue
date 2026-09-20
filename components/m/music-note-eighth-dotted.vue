<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myr8txt8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myr8txt8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-eighth-dotted" /></template>
