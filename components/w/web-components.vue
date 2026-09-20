<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9trap0en.css';
import '../../css/i/iy-inqwow.css';
import '../../css/e/e_ypaqv-x.css';
import '../../css/f/f6_detbwu.css';
import '../../css/x/xlz5h_bpg.css';
import '../../css/d/d03o239fy.css';
import '../../css/e/e_uk5ubit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k9trap0en"/><path class="iy-inqwow"/><path class="e_ypaqv-x"/><path class="f6_detbwu"/><path class="xlz5h_bpg"/><path class="d03o239fy"/><path class="e_uk5ubit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:web-components" /></template>
