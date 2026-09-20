<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcowhso_o.css';
import '../../css/v/vnjuuubcl.css';
import '../../css/o/oxuzwkbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcowhso_o"/><path class="vnjuuubcl"/><path class="oxuzwkbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ringlink" /></template>
