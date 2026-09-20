<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbqtwbcin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbqtwbcin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:martial-arts-swords" /></template>
