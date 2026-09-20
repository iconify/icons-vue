<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjdstubtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjdstubtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:player-phone-station-1-bold" /></template>
