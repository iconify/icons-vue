<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzj803jut.css';
import '../../css/s/s4_r7ab8r.css';
import '../../css/n/nk949cczd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzj803jut"/><path class="s4_r7ab8r"/><path class="nk949cczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-ribbon" /></template>
