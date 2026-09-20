<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k47fgybkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k47fgybkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-tiles-light" /></template>
