<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksc5z13bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksc5z13bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:utorrent-light" /></template>
