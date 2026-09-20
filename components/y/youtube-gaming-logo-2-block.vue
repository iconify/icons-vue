<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqrbpbc4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mqrbpbc4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-gaming-logo-2-block" /></template>
