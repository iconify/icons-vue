<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx13v7buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx13v7buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-direktetv" /></template>
