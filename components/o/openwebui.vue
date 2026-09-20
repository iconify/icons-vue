<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx5d-bc1s.css';
import '../../css/g/g9od2_b1c.css';
import '../../css/g/gexzjokqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nx5d-bc1s"><path clip-rule="evenodd" class="g9od2_b1c"/><path class="gexzjokqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openwebui" /></template>
