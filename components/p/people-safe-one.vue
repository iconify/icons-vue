<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/ikbleibbz.css';
import '../../css/u/ue1cjpbqo.css';
import '../../css/r/rw886cb0d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSFxUlezu"><g class="aql7dnt-u"><circle class="ikbleibbz"/><path class="ue1cjpbqo"/><path class="rw886cb0d"/></g></mask></defs><path mask="url(#SVGSFxUlezu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people-safe-one" /></template>
