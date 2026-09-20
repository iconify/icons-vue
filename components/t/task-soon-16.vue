<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdrw_-bzd.css';
import '../../css/m/m0a6ogbci.css';
import '../../css/d/deo436eby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fdrw_-bzd"/><path class="m0a6ogbci"/><path clip-rule="evenodd" class="deo436eby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:task-soon-16" /></template>
