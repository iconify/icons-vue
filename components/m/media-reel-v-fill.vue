<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0yfsub-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0yfsub-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:media-reel-v-fill" /></template>
