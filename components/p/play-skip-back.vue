<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg6d2vd4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mg6d2vd4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-skip-back" /></template>
