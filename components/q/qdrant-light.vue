<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2gmwachp.css';
import '../../css/q/qs06oviiv.css';
import '../../css/l/lhdmhjbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2gmwachp"/><path class="qs06oviiv"/><path class="lhdmhjbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qdrant-light" /></template>
