<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg7dfsboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hg7dfsboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-2-outline" /></template>
