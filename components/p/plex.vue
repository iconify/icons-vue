<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hojbiib5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hojbiib5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:plex" /></template>
