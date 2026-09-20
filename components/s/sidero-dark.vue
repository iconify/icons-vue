<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsdydjp4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsdydjp4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sidero-dark" /></template>
