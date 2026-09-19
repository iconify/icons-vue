<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykl75acdx.css';
import '../../css/u/uvdwn1_nw.css';
import '../../css/b/bg9eedant.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ykl75acdx"/><path class="uvdwn1_nw"/><path class="bg9eedant"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-baseball" /></template>
