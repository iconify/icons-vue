<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mrm-b0b6w.css';
import '../../css/m/md286fbip.css';
import '../../css/m/mby9vxbvb.css';
import '../../css/k/ke0ekgt1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="mrm-b0b6w"/><g class="md286fbip"><path class="mby9vxbvb"/><path class="ke0ekgt1o"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:tks" /></template>
