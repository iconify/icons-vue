<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7giafb7e.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/z/z0pt6bbyk.css';
import '../../css/j/jcsbf6brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e7giafb7e"/><g class="n1mjunbsu"><path class="z0pt6bbyk"/><path class="jcsbf6brg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:plus" /></template>
