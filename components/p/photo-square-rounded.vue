<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/ur7rt5fas.css';
import '../../css/e/eg76xwbic.css';
import '../../css/j/jno4cqb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ur7rt5fas"/><path class="eg76xwbic"/><path class="jno4cqb6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:photo-square-rounded" /></template>
