<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrjwib-mi.css';
import '../../css/h/hlu7_ghbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrjwib-mi"/><path class="hlu7_ghbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-thunderstorm" /></template>
