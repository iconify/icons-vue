<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/sfqkxp9kj.css';
import '../../css/v/v08-a-n6j.css';
import '../../css/o/oi80i7wcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sfqkxp9kj"/><path class="v08-a-n6j"/><path class="oi80i7wcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:ship-cargo" /></template>
