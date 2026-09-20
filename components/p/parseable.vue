<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0p0fbb2l.css';
import '../../css/t/tsx8_8m-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0p0fbb2l"/><path class="tsx8_8m-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:parseable" /></template>
