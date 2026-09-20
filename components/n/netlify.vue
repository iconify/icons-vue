<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntrj6wbus.css';
import '../../css/l/lc00ugj9n.css';
import '../../css/q/q8d85yv9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGASdr6dgl" cx="-90.77" cy="-7.597" r="13.368" gradientTransform="matrix(0 38.301 -44.1228 0 -79.191 3476.303)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ntrj6wbus"/><stop offset="1" class="lc00ugj9n"/></radialGradient><path fill="url(#SVGASdr6dgl)" class="q8d85yv9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netlify" /></template>
