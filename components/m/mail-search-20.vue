<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tixg4gbgk.css';
import '../../css/o/ox2_dgbyg.css';
import '../../css/c/cgo_eslee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tixg4gbgk"/><path class="ox2_dgbyg"/><path class="cgo_eslee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-search-20" /></template>
