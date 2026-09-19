<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak5m796zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak5m796zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-forward-circle" /></template>
