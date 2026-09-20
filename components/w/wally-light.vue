<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myfiu2y2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="myfiu2y2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wally-light" /></template>
