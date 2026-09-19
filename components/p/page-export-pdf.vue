<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4w_9_brk.css';
import '../../css/h/h4t1d2bui.css';
import '../../css/o/o2c4vcs2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="n4w_9_brk"/><path class="h4t1d2bui"/><path class="o2c4vcs2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-export-pdf" /></template>
