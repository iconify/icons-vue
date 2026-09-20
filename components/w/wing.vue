<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7ywrlbnk.css';
import '../../css/p/p0jv7ib7i.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/t/tu2z8fb9g.css';
import '../../css/e/e9rmuj2zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="m7ywrlbnk"/><path class="p0jv7ib7i"/><g class="jn8qy4bru"><path class="tu2z8fb9g"/><path class="e9rmuj2zs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wing" /></template>
