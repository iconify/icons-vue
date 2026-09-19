<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ak8q7sy8o.css';
import '../../css/h/h_267dbvz.css';
import '../../css/y/y650zr1fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ak8q7sy8o"/><path class="h_267dbvz"/><path class="y650zr1fk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:nf" /></template>
