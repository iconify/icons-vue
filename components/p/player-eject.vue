<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu28otbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu28otbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-eject" /></template>
