<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiwvyc24j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiwvyc24j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:music-note-solid" /></template>
