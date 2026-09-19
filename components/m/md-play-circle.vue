<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ombmqu5rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ombmqu5rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-play-circle" /></template>
