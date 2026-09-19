<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_3v7yb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_3v7yb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:spotify-filled" /></template>
