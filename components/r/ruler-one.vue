<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/d/d4_zcpqsz.css';
import '../../css/f/fg8q2v5iw.css';
import '../../css/f/fvpo9wbmn.css';
import '../../css/o/o6ow2nvyg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGQoOxbQl"><g class="hv130ab-t"><path class="d4_zcpqsz"/><path class="fg8q2v5iw"/><path class="fvpo9wbmn"/><path class="o6ow2nvyg"/></g></mask></defs><path mask="url(#SVGGQoOxbQl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:ruler-one" /></template>
