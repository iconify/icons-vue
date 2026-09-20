<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d60x365_f.css';
import '../../css/x/xm0m4wb9x.css';
import '../../css/r/r2tvs_tus.css';
import '../../css/i/ioxrwsrea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":228,"height":198};
const content = `<path class="d60x365_f"/><path class="xm0m4wb9x"/><path class="r2tvs_tus"/><path class="ioxrwsrea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:midudev" /></template>
