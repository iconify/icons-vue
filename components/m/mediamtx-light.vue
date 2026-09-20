<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds0s6f9to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds0s6f9to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamtx-light" /></template>
