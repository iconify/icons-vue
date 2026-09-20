<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1qdg1bld.css';
import '../../css/s/s519vbn7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k1qdg1bld"/><path class="s519vbn7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thingiverse" /></template>
