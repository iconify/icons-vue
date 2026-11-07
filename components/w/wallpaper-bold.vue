<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4-r16bpz.css';
import '../../css/c/c0abhhbxc.css';
import '../../css/b/bu3d-6cof.css';
import '../../css/x/xnmzdybto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4-r16bpz"/><path class="c0abhhbxc"/><path class="bu3d-6cof"/><path clip-rule="evenodd" class="xnmzdybto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallpaper-bold" /></template>
