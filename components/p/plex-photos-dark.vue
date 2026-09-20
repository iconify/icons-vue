<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujctd5tks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujctd5tks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plex-photos-dark" /></template>
