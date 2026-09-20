<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8lk1hb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z8lk1hb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:music-note" /></template>
