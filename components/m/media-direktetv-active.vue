<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5212tb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5212tb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-direktetv-active" /></template>
