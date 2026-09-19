<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/bdr4wv3bp.css';
import '../../css/p/p64iu1blt.css';
import '../../css/c/ck0qv6bfm.css';
import '../../css/t/th5tstbfr.css';
import '../../css/r/r4q61bcud.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZmRzmdso"><g class="s9cl3zbei"><rect class="bdr4wv3bp"/><path class="p64iu1blt"/><path class="ck0qv6bfm"/><circle class="th5tstbfr"/><path class="r4q61bcud"/></g></mask></defs><path mask="url(#SVGZmRzmdso)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:medication-time" /></template>
