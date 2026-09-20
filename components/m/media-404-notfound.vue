<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hph7rtbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hph7rtbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-404-notfound" /></template>
