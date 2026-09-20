<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwnw3gb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwnw3gb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:twitch" /></template>
