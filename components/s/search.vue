<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uop2qebfk.css';
import '../../css/e/ekm40idyc.css';
import '../../css/s/s64pf7cve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uop2qebfk"/><path class="ekm40idyc"/><path class="s64pf7cve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:search" /></template>
