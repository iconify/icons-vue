<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2v-92ycv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2v-92ycv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onenote-2013-light" /></template>
