<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swk2k98ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="swk2k98ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-folder-song-solid" /></template>
