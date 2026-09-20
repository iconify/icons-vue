<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsmli1cfn.css';
import '../../css/x/xfegddcoa.css';
import '../../css/u/u5r3t04hl.css';
import '../../css/i/i0k6moa8q.css';
import '../../css/g/g9u-te31s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="nsmli1cfn"/><path class="xfegddcoa"/><path class="u5r3t04hl"/><path class="i0k6moa8q"/><path class="g9u-te31s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tiny-tiny-rss" /></template>
