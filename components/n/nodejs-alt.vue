<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhb4zef1o.css';
import '../../css/y/yd_4pqb_b.css';
import '../../css/d/di3r7bqli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nhb4zef1o"/><path class="yd_4pqb_b"/><path class="di3r7bqli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nodejs-alt" /></template>
