<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joot-gj4s.css';
import '../../css/m/mdm2icu2v.css';
import '../../css/o/oc6ekbbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="joot-gj4s"/><path clip-rule="evenodd" class="mdm2icu2v"/><path class="oc6ekbbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-alpha-asc-16" /></template>
