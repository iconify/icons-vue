<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue4lfcc1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ue4lfcc1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:more-active" /></template>
