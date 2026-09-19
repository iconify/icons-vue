<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy3p094dk.css';
import '../../css/j/j_7wf_9wv.css';
import '../../css/d/dk5jy9x_q.css';
import '../../css/m/mf_n5zbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jy3p094dk"/><path class="j_7wf_9wv"/><path class="dk5jy9x_q"/><path class="mf_n5zbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stress-breath-editor" /></template>
