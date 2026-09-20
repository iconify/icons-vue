<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erw718bqg.css';
import '../../css/g/g8uv-0b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="erw718bqg"/><path class="g8uv-0b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:raised-back-of-hand" /></template>
