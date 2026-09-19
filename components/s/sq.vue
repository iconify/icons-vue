<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/wj-7246uw.css';
import '../../css/a/aev8zfb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsSq0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsSq0)"><path class="wj-7246uw"/><path class="aev8zfb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:sq" /></template>
