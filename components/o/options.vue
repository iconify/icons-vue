<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puid7l1ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="puid7l1ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:options" /></template>
