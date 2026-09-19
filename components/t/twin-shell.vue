<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdlbsc1hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdlbsc1hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:twin-shell" /></template>
