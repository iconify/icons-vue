<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf20vue0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf20vue0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-eject-filled" /></template>
