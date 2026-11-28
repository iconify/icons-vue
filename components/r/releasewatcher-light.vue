<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqrll5btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqrll5btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:releasewatcher-light" /></template>
