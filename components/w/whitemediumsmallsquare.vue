<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq-gx3bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cq-gx3bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitemediumsmallsquare" /></template>
