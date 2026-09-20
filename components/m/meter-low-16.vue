<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrbv2j1ga.css';
import '../../css/q/qtl0jcblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xrbv2j1ga"/><path class="qtl0jcblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:meter-low-16" /></template>
