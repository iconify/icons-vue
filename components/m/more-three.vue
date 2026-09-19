<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x36h_kb1w.css';
import '../../css/b/bbzwh_4tl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHmRZQdpG"><g class="ft5dv1b6b"><path class="x36h_kb1w"/><path clip-rule="evenodd" class="bbzwh_4tl"/></g></mask></defs><path mask="url(#SVGHmRZQdpG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:more-three" /></template>
