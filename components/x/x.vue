<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/db51_1bbb.css';
import '../../css/m/md286fbip.css';
import '../../css/d/diq9bpbfb.css';
import '../../css/j/jz9h9rb4r.css';
import '../../css/e/e4utglbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="db51_1bbb"/><g class="md286fbip"><path class="diq9bpbfb"/><path class="jz9h9rb4r"/><path class="e4utglbqp"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:x" /></template>
