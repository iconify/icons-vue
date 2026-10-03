<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugm2nob5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugm2nob5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zenmux-light" /></template>
