<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in6lw_b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in6lw_b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rustpad-light" /></template>
