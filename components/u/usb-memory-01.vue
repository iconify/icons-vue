<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/ao10ozfpq.css';
import '../../css/c/c2bfh4dgq.css';
import '../../css/o/orzk3obqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ao10ozfpq"/><path class="c2bfh4dgq"/><path class="orzk3obqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:usb-memory-01" /></template>
