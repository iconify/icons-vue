<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/w/wnfe9p2uz.css';
import '../../css/r/r-mrtlb8m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzcZtSACT"><g class="hv130ab-t"><rect transform="rotate(-45 17 24.071)" class="wnfe9p2uz"/><path class="r-mrtlb8m"/></g></mask></defs><path mask="url(#SVGzcZtSACT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:refresh-one" /></template>
