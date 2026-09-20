<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b731rmehh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b731rmehh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:music-note-slash" /></template>
