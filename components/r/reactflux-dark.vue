<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-j1wjl-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-j1wjl-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reactflux-dark" /></template>
