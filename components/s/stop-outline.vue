<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/i/imnimkbei.css';
import '../../css/z/zqzy3hb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="to-5kdesz"><path class="imnimkbei"/><path class="zqzy3hb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:stop-outline" /></template>
