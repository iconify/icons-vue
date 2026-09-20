<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzh9wkb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dzh9wkb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-folder-song-remix" /></template>
