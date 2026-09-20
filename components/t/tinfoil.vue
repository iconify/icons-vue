<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk7wtbc2i.css';
import '../../css/t/tqqkmcc0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wk7wtbc2i"/><path class="tqqkmcc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tinfoil" /></template>
