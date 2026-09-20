<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw3_0y36g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gw3_0y36g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-letter-boxed-light" /></template>
