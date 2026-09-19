<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v92du4b9z.css';
import '../../css/l/l7b_ym2oe.css';
import '../../css/q/qw0bgzezr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v92du4b9z"/><path class="l7b_ym2oe"/><path class="qw0bgzezr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thunderstorm-severe" /></template>
