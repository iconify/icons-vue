<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcgr1exts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcgr1exts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rock-and-roll-hand-solid" /></template>
