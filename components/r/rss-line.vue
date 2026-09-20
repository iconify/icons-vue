<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wav0n5hso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wav0n5hso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rss-line" /></template>
