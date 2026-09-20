<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm5_ombgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gm5_ombgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voxmedia-coral-light" /></template>
