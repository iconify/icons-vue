<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7mgyobwh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVVTypbHn"><path class="f7mgyobwh"/></mask></defs><path mask="url(#SVGVVTypbHn)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:play-one" /></template>
