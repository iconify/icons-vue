<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gev-dachs.css';
import '../../css/u/unw373bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gev-dachs"/><path class="unw373bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sidewaysblackrightpointingindex" /></template>
