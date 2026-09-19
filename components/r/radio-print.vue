<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/r/re2szxb9s.css';
import '../../css/p/pqb5v7bov.css';
import '../../css/v/v39gkbo3f.css';
import '../../css/h/h9rbmc90b.css';
import '../../css/t/tdaae9bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="re2szxb9s"/><path clip-rule="evenodd" class="pqb5v7bov"/></g><path clip-rule="evenodd" class="v39gkbo3f"/><path class="h9rbmc90b"/><path clip-rule="evenodd" class="tdaae9bql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:radio-print" /></template>
