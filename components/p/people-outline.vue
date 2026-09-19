<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnfili8xo.css';
import '../../css/n/nnly1dl6q.css';
import '../../css/p/p2ysx8bbc.css';
import '../../css/z/zbo3cxv1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnfili8xo"/><path class="nnly1dl6q"/><path class="p2ysx8bbc"/><path class="zbo3cxv1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:people-outline" /></template>
