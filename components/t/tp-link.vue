<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzam9lb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzam9lb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tp-link" /></template>
