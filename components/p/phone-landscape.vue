<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x50z2w0vt.css';
import '../../css/u/ujlm800om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVG5mxdJbfR" class="x50z2w0vt"/></defs><use href="#SVG5mxdJbfR"/><path class="ujlm800om"/><use href="#SVG5mxdJbfR"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:phone-landscape" /></template>
