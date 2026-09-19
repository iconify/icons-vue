<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfxfn_o5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nfxfn_o5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-heart-half" /></template>
