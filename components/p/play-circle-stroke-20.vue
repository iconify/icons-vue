<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noz2g8nyr.css';
import '../../css/r/r6f3racak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="noz2g8nyr"/><path class="r6f3racak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-circle-stroke-20" /></template>
