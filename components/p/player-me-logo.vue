<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6067ebcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6067ebcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:player-me-logo" /></template>
