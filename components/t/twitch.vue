<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-yjszb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-yjszb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:twitch" /></template>
