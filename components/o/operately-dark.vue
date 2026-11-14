<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw8tm-bwd.css';
import '../../css/u/u-8cambew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pw8tm-bwd"/><path class="u-8cambew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:operately-dark" /></template>
