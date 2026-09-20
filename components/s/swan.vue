<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxouekb2m.css';
import '../../css/a/agfevld8e.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/a/axggxtb5f.css';
import '../../css/a/at49vymej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yxouekb2m"/><path class="agfevld8e"/><g class="jn8qy4bru"><path class="axggxtb5f"/><path class="at49vymej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:swan" /></template>
