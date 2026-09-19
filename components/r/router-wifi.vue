<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2qg-ubuc.css';
import '../../css/u/u5et5qd9b.css';
import '../../css/m/mab01i4rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="l2qg-ubuc"/><path class="u5et5qd9b"/><path class="mab01i4rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:router-wifi" /></template>
