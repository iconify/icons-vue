<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csdw9chgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="csdw9chgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-eject" /></template>
