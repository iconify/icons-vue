<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t__y3ywkr.css';
import '../../css/o/ocjdsognq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t__y3ywkr"/><path class="ocjdsognq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-skip-backward" /></template>
