<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/j/j222h5b5x.css';
import '../../css/d/d7aug1b2m.css';
import '../../css/e/e5jk9c-yn.css';
import '../../css/g/gqizmlvif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsTe0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsTe0)"><path class="j222h5b5x"/><path class="d7aug1b2m"/><path class="e5jk9c-yn"/><path class="gqizmlvif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:te" /></template>
