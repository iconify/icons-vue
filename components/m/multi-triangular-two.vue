<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/q-pan9bpu.css';
import '../../css/n/ni2kn61-e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNj5d8daY"><g class="aql7dnt-u"><path class="q-pan9bpu"/><path class="ni2kn61-e"/></g></mask></defs><path mask="url(#SVGNj5d8daY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:multi-triangular-two" /></template>
