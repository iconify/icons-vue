<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpy_g2b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jpy_g2b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:x-p-ferd-light" /></template>
