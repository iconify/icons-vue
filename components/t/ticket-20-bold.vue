<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq6qzmbna.css';
import '../../css/r/r0r74pb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yq6qzmbna"/><path class="r0r74pb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ticket-20-bold" /></template>
