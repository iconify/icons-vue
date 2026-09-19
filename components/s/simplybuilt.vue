<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnkm-ebgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1600};
const content = `<path class="fnkm-ebgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:simplybuilt" /></template>
