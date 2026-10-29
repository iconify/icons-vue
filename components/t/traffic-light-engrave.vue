<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gwth-_hib.css';
import '../../css/j/jd7su4bny.css';
import '../../css/o/o2v087bye.css';
import '../../css/h/hqyg-9bir.css';
import '../../css/p/p0q2sxjnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gwth-_hib wm-k"/><path class="jd7su4bny wm-a"/><path class="o2v087bye wm-shadow"/><path class="hqyg-9bir wm-k"/><path class="p0q2sxjnz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:traffic-light-engrave" /></template>
