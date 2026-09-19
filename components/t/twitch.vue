<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhzhsy8bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhzhsy8bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:twitch" /></template>
