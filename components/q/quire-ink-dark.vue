<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcxgohb4h.css';
import '../../css/x/xbefkzbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcxgohb4h"/><path class="xbefkzbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quire-ink-dark" /></template>
