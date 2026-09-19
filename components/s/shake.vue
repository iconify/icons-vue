<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/a3egu4bnj.css';
import '../../css/k/k_94f0bqu.css';
import '../../css/z/zri7a6b5o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGagp6hcaK"><g class="v3_i3wktz"><path class="a3egu4bnj"/><path class="k_94f0bqu"/><path class="zri7a6b5o"/></g></mask></defs><path mask="url(#SVGagp6hcaK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:shake" /></template>
