<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lgn46h21v.css';
import '../../css/o/oai5is-6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<rect class="cuyn6tgcc"/><g class="cuyn6tgcc"><path class="lgn46h21v"/><g transform="translate(-18.436 -431.962)"><circle/><path class="oai5is-6o"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:uwsgi" /></template>
