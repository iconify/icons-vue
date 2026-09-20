<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84xo7bjy.css';
import '../../css/o/okm7grcet.css';
import '../../css/o/oeuv6sbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w84xo7bjy"/><path class="okm7grcet"/><path class="oeuv6sbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-watcher" /></template>
