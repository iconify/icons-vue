<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0gw__81g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p0gw__81g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:paw" /></template>
