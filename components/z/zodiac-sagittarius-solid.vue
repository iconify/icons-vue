<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut-0zoohp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut-0zoohp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-sagittarius-solid" /></template>
