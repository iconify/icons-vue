<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_cyjh5hd.css';
import '../../css/r/r8bd01bug.css';
import '../../css/d/d8mvshbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n_cyjh5hd"><path class="r8bd01bug"/><path class="d8mvshbpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-vert-square-line" /></template>
