<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqjreok_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qqjreok_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:speedtest-dark" /></template>
