<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfzzc2b4k.css';
import '../../css/e/e558ozb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zfzzc2b4k"/><path class="e558ozb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasa-light" /></template>
