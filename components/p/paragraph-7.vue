<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgg9tabhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgg9tabhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:paragraph-7" /></template>
