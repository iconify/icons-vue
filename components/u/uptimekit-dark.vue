<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy6o-6bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qy6o-6bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimekit-dark" /></template>
