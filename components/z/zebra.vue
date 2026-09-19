<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s2ynf1bfe.css';
import '../../css/b/b7zywacgj.css';
import '../../css/o/o2o1avb3g.css';
import '../../css/l/lo-d6dbbx.css';
import '../../css/a/aczdb44rv.css';
import '../../css/p/pioi3cnkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="s2ynf1bfe"/><path class="b7zywacgj"/><path class="o2o1avb3g"/><path class="lo-d6dbbx"/><path class="aczdb44rv"/><path class="pioi3cnkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:zebra" /></template>
