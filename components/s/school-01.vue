<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jrr___b0r.css';
import '../../css/g/gzovhsluf.css';
import '../../css/f/f2tulrb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jrr___b0r"/><path class="gzovhsluf"/><path class="f2tulrb0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:school-01" /></template>
