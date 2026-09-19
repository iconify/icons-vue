<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99j2sggn.css';
import '../../css/r/rswgeacvu.css';
import '../../css/z/zidxczbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t99j2sggn"/><path class="rswgeacvu"/><path class="zidxczbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:redux" /></template>
