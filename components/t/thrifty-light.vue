<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1e0ebb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1e0ebb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thrifty-light" /></template>
