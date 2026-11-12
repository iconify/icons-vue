<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiu53fbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yiu53fbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storyteller-light" /></template>
