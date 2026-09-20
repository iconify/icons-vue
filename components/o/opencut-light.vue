<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw402bc7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iw402bc7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opencut-light" /></template>
