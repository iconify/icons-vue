<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcwj51wla.css';
import '../../css/d/dxldknbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcwj51wla"/><path class="dxldknbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-bold-duotone" /></template>
