<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f62xxfveg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f62xxfveg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-play-thin" /></template>
