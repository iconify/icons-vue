<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/utj8jebkl.css';
import '../../css/t/ty4gwj7hq.css';
import '../../css/o/o9747sblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="utj8jebkl"/><path class="ty4gwj7hq"/><path class="o9747sblf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:radar" /></template>
