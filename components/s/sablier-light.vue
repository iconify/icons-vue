<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrp8vu0zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrp8vu0zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sablier-light" /></template>
