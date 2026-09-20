<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxfif4y9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxfif4y9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonatype-nexus-repository-light" /></template>
