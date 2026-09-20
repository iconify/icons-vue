<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwad_gb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwad_gb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minimus-dark" /></template>
