<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x50z2w0vt.css';
import '../../css/u/ujlm800om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVGNnUjDexH" class="x50z2w0vt"/></defs><use href="#SVGNnUjDexH"/><path class="ujlm800om"/><use href="#SVGNnUjDexH"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:phone-landscape" /></template>
