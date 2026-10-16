<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihmii9b0s.css';
import '../../css/w/w-me-sb1b.css';
import '../../css/u/urmzceb0n.css';
import '../../css/b/b-1wnc-ph.css';
import '../../css/a/a6j7g-bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihmii9b0s"/><path class="w-me-sb1b"/><path class="urmzceb0n"/><path class="b-1wnc-ph"/><path class="a6j7g-bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tree-planting-48-bold" /></template>
