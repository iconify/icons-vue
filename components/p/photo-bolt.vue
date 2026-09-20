<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/o6kj1gvby.css';
import '../../css/h/hn7lp_bzn.css';
import '../../css/n/n6w939bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o6kj1gvby"/><path class="hn7lp_bzn"/><path class="n6w939bna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:photo-bolt" /></template>
