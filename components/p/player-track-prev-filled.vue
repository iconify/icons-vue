<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_lf64b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_lf64b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-track-prev-filled" /></template>
