<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc9xoccqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uc9xoccqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-programguide" /></template>
