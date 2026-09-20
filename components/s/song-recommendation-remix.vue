<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvmp5sbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvmp5sbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:song-recommendation-remix" /></template>
