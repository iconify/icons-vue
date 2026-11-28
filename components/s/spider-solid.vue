<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ns25x2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7ns25x2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spider-solid" /></template>
