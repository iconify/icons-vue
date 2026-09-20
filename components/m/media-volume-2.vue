<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze58a6bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze58a6bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-volume-2" /></template>
