<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/v/voxy1aceb.css';
import '../../css/j/jbjhzw2kz.css';
import '../../css/n/nlnyzpbpz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHwVmOb8z"><g class="aql7dnt-u"><path class="voxy1aceb"/><path class="jbjhzw2kz"/><path class="nlnyzpbpz"/></g></mask></defs><path mask="url(#SVGHwVmOb8z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tent" /></template>
