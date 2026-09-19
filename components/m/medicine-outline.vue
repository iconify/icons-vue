<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/s6cukem8f.css';
import '../../css/b/bvdi23b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="medicine-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="s6cukem8f"/><path class="bvdi23b-c"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:medicine-outline" /></template>
