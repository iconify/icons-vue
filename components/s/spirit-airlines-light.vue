<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ci1vbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_ci1vbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spirit-airlines-light" /></template>
