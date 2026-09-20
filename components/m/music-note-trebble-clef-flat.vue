<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ho2kyto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_ho2kyto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:music-note-trebble-clef-flat" /></template>
