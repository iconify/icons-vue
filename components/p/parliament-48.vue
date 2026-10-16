<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfzcs1bmb.css';
import '../../css/x/xf-7edb6n.css';
import '../../css/a/aw8zs8bon.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfzcs1bmb"/><path class="xf-7edb6n"/><path class="aw8zs8bon"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parliament-48" /></template>
