<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddkf61byi.css';
import '../../css/s/s45cdxblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ddkf61byi"/><path class="s45cdxblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reveal-js" /></template>
