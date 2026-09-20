<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr5n7bbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sr5n7bbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qemu-dark" /></template>
