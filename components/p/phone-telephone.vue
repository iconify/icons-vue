<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eknmiedkj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaJDgL3dK"><path class="eknmiedkj"/></mask></defs><path mask="url(#SVGaJDgL3dK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:phone-telephone" /></template>
