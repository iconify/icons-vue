<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv2q8ftgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dv2q8ftgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-play-fill" /></template>
