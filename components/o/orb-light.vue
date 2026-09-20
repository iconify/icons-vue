<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lldu6nt-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lldu6nt-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orb-light" /></template>
