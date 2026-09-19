<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc2gdbbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zc2gdbbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:patreon" /></template>
