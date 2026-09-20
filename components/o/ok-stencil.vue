<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df7-84bmu.css';
import '../../css/w/whpncgbes.css';
import '../../css/l/lbxg3kb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="df7-84bmu"/><path class="whpncgbes"/><path class="lbxg3kb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ok-stencil" /></template>
