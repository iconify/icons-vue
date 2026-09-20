<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l67hr4bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="l67hr4bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:media-player" /></template>
