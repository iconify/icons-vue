<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc3icy34w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vc3icy34w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr-anime-light" /></template>
