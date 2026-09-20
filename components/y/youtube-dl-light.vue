<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lja0s1wsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lja0s1wsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-dl-light" /></template>
