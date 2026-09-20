<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlah1ebhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nlah1ebhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mergerfs-dark" /></template>
