<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4-vtpbnb.css';
import '../../css/x/xtnibnbva.css';
import '../../css/h/hn9ztn5zb.css';
import '../../css/a/aszoa8b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4-vtpbnb"/><path class="xtnibnbva"/><path class="hn9ztn5zb"/><path class="aszoa8b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thrifty" /></template>
