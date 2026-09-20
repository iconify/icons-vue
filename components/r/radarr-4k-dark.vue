<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3iteg4cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3iteg4cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr-4k-dark" /></template>
