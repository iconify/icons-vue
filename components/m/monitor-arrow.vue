<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hrsklvb_e.css';
import '../../css/a/acgeldc-e.css';
import '../../css/b/bmcgo5b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="hrsklvb_e"/><path class="acgeldc-e"/><path class="bmcgo5b3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:monitor-arrow" /></template>
