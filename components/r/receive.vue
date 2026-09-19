<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/x/xy8i4w10j.css';
import '../../css/w/wlqvjmcwi.css';
import '../../css/t/tx7e6g5tu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAIFe7bVL"><g class="hv130ab-t"><path class="xy8i4w10j"/><path class="wlqvjmcwi"/><path class="tx7e6g5tu"/></g></mask></defs><path mask="url(#SVGAIFe7bVL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:receive" /></template>
