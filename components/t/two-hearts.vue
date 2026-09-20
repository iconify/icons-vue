<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai0cm1bnr.css';
import '../../css/z/z6ro75yjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ai0cm1bnr"/><path class="z6ro75yjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:two-hearts" /></template>
