<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u95q25xah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u95q25xah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:note-1-off" /></template>
