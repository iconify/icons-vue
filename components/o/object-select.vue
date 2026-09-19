<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b_ji3pbxg.css';
import '../../css/h/ho8edbc3c.css';
import '../../css/v/v9tvw21br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b_ji3pbxg"/><path class="ho8edbc3c"/><path class="v9tvw21br"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:object-select" /></template>
