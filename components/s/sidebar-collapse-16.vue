<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj57gablw.css';
import '../../css/z/zqhih1b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oj57gablw"/><path class="zqhih1b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sidebar-collapse-16" /></template>
