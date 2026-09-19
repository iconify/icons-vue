<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/a/ayrm58b3o.css';
import '../../css/m/mfzbs70ff.css';
import '../../css/n/n4cyhmbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsUdm0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsUdm0)"><path class="ayrm58b3o"/><path class="mfzbs70ff"/><path class="n4cyhmbkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:udm" /></template>
