<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j14wnj9wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j14wnj9wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptime-kuma-dark" /></template>
