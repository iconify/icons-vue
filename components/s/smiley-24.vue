<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-wc5tbnn.css';
import '../../css/z/zj49idy7n.css';
import '../../css/p/psb8q1--l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-wc5tbnn"/><path class="zj49idy7n"/><path class="psb8q1--l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:smiley-24" /></template>
