<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwr2epb-t.css';
import '../../css/s/swf58-3sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vwr2epb-t"/><path class="swf58-3sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oxicloud" /></template>
