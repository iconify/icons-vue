<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma83kwbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ma83kwbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonatype-nexus-repository-dark" /></template>
