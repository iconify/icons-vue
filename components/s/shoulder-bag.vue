<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mmnjdfbni.css';
import '../../css/f/f2r7aqcds.css';
import '../../css/t/tt4z5sb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="mmnjdfbni"/><path class="f2r7aqcds"/><circle class="tt4z5sb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:shoulder-bag" /></template>
