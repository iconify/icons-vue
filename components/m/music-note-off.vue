<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs4b65bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs4b65bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:music-note-off" /></template>
