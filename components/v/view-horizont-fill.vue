<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g7v2-ye3h.css';
import '../../css/r/rfrpfefci.css';
import '../../css/e/eg4pfcc0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g7v2-ye3h"/><path class="rfrpfefci"/><path clip-rule="evenodd" class="eg4pfcc0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:view-horizont-fill" /></template>
