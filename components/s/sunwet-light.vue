<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhswl84tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bhswl84tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sunwet-light" /></template>
