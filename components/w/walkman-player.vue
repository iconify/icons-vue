<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc87u0btn.css';
import '../../css/f/fs_fwv3jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc87u0btn"/><path class="fs_fwv3jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:walkman-player" /></template>
