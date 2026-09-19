<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/cweuz1bja.css';
import '../../css/v/v1rs_9bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(1)" class="n1lsf0bnc"><circle class="cweuz1bja"/><path class="v1rs_9bxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:tennis-racket-ball" /></template>
