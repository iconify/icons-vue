<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/damb695lr.css';
import '../../css/g/gwkoec6sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="d2kvgvbvc"><path class="damb695lr"/><path class="gwkoec6sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:pl-4x3" /></template>
