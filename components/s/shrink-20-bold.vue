<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovky5ebwk.css';
import '../../css/e/e0581abux.css';
import '../../css/v/vkg-d9byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ovky5ebwk"/><path class="e0581abux"/><path class="vkg-d9byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shrink-20-bold" /></template>
