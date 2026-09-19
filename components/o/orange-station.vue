<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/frzwsccnm.css';
import '../../css/c/c74-wy8tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="d2kvgvbvc"><path class="frzwsccnm"/><path class="c74-wy8tu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:orange-station" /></template>
