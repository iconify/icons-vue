<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sg937_1md.css';
import '../../css/b/bbthzgo7i.css';
import '../../css/j/jef6gtb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="sg937_1md"/><path class="bbthzgo7i"/><path clip-rule="evenodd" class="jef6gtb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:painted-eggshell" /></template>
