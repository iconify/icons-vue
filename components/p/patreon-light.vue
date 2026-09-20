<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha51odben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ha51odben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:patreon-light" /></template>
