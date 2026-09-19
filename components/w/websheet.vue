<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbfjszvql.css';
import '../../css/q/qstm5aclq.css';
import '../../css/u/u9olyabjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="tbfjszvql"/><path class="qstm5aclq"/><path class="u9olyabjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:websheet" /></template>
