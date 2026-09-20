<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5unoophq.css';
import '../../css/e/elvlbwvzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p5unoophq"/><path class="elvlbwvzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:marketing-filled" /></template>
