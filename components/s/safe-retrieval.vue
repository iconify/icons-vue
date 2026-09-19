<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/q7rv1wb0c.css';
import '../../css/o/o8mr_30le.css';
import '../../css/q/q8ugq6w2c.css';
import '../../css/i/irl1o9bvn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPoap6clH"><g class="v3_i3wktz"><path class="q7rv1wb0c"/><path class="o8mr_30le"/><path class="q8ugq6w2c"/><path class="irl1o9bvn"/></g></mask></defs><path mask="url(#SVGPoap6clH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:safe-retrieval" /></template>
