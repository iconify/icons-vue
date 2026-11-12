<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ttwubdw.css';
import '../../css/v/vxrrplwnx.css';
import '../../css/b/bwdyegfbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-ttwubdw"/><path class="vxrrplwnx"/><path class="bwdyegfbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marp-dark" /></template>
