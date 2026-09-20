<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_pewl6-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_pewl6-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postcard-light" /></template>
