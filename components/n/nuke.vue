<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9b346mxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9b346mxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nuke" /></template>
