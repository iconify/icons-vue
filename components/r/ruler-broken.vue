<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cz11_obym.css';
import '../../css/d/dbce2h2td.css';
import '../../css/p/pf4lixn8e.css';
import '../../css/z/z4t16fbxy.css';
import '../../css/j/jdt4fscuq.css';
import '../../css/m/m70uymbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cz11_obym"/><path class="dbce2h2td"/><path class="pf4lixn8e"/><path class="z4t16fbxy"/><path class="jdt4fscuq"/><path class="m70uymbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-broken" /></template>
