<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyv3_ubgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyv3_ubgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-play-filled" /></template>
