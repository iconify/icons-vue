<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq3r5fw2r.css';
import '../../css/i/i_d2xgsxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="lq3r5fw2r"/><path class="i_d2xgsxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:scale-outline" /></template>
