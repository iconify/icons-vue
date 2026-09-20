<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9pu_gbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9pu_gbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twitch-light" /></template>
