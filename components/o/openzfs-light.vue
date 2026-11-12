<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8a7jsb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8a7jsb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openzfs-light" /></template>
