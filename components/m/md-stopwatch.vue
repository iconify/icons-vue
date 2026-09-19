<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvv_78wpo.css';
import '../../css/c/cecp9abjx.css';
import '../../css/j/jr0laybrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cvv_78wpo"/><path class="cecp9abjx"/><path class="jr0laybrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-stopwatch" /></template>
