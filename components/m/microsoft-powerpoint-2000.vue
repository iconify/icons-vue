<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb6qy0bak.css';
import '../../css/q/qtm7ddo2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hb6qy0bak"/><path class="qtm7ddo2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-2000" /></template>
