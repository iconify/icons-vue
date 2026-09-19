<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqd8fcboz.css';
import '../../css/d/dzr6cgbld.css';
import '../../css/p/pg7ja1biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><path class="dzr6cgbld"/><path class="pg7ja1biu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gala:video" /></template>
