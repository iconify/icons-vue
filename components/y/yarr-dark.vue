<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9el3bc1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9el3bc1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yarr-dark" /></template>
