<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnpg-xbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nnpg-xbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:play-circle" /></template>
