<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dgugneb_n.css';
import '../../css/i/ink891bfz.css';
import '../../css/g/gvlki0bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dgugneb_n"/><path class="ink891bfz"/><path class="gvlki0bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-add-01" /></template>
