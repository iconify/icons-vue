<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evs_ze2wt.css';
import '../../css/r/rge2six-h.css';
import '../../css/y/ycgbuscwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="evs_ze2wt"/><path class="rge2six-h"/><path class="ycgbuscwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:spicedb" /></template>
