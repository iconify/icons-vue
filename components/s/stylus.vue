<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tybcrmi-m.css';
import '../../css/b/bsvdiixhm.css';
import '../../css/r/r_9lwu93i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="tybcrmi-m"><path class="bsvdiixhm"/><path class="r_9lwu93i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stylus" /></template>
