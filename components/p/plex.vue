<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_oop1bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_oop1bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:plex" /></template>
