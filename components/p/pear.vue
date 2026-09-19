<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aj_c07b7j.css';
import '../../css/w/w1ex1ky4b.css';
import '../../css/x/xq9btcbaq.css';
import '../../css/x/x0_lnze0l.css';
import '../../css/z/z0pl7gbbw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhUCLHbot"><g class="ft5dv1b6b"><path class="aj_c07b7j"/><path class="w1ex1ky4b"/><circle class="xq9btcbaq"/><circle class="x0_lnze0l"/><circle class="z0pl7gbbw"/></g></mask></defs><path mask="url(#SVGhUCLHbot)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pear" /></template>
