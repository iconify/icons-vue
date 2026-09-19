<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj615pbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj615pbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:superscript" /></template>
