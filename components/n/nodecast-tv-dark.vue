<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/way8m64gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="way8m64gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nodecast-tv-dark" /></template>
