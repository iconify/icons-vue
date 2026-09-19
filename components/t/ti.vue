<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/z/zft_32b5b.css';
import '../../css/d/dx0ia8cmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsTi0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsTi0)"><path class="zft_32b5b"/><path class="dx0ia8cmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:ti" /></template>
