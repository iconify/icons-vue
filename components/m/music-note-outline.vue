<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmmehnb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gmmehnb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:music-note-outline" /></template>
