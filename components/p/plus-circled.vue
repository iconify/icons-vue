<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omst-ztto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omst-ztto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:plus-circled" /></template>
