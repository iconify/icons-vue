<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/o/o7-xvcqli.css';
import '../../css/e/e6pmp0b8v.css';
import '../../css/r/r1dv0f0sg.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGxVkgLcUD"><path class="k5-vjlrin"/><g transform="translate(3 3)" class="o7-xvcqli"><circle class="e6pmp0b8v"/><path class="r1dv0f0sg"/></g></mask></defs><circle mask="url(#SVGxVkgLcUD)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:person-circle-filled" /></template>
