<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z7ckrwbnn.css';
import '../../css/l/l3ix8-b0t.css';
import '../../css/z/zg5fcjbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="z7ckrwbnn"/><path class="l3ix8-b0t"/><path class="zg5fcjbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-02" /></template>
