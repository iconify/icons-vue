<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8ql71r8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8ql71r8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:protondb-dark" /></template>
