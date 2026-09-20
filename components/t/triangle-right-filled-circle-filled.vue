<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/k/kax-q9blx.css';
import '../../css/h/hsit5q6hy.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGMOmoucTs"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="kax-q9blx"/><path class="hsit5q6hy"/></g></mask></defs><circle mask="url(#SVGMOmoucTs)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:triangle-right-filled-circle-filled" /></template>
