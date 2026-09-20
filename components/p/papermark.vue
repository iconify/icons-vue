<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n11xp5baq.css';
import '../../css/a/a61ltbq0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path vector-effect="non-scaling-stroke" class="n11xp5baq"/><path class="a61ltbq0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermark" /></template>
