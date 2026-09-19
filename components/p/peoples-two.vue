<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/p/p1r_41bpz.css';
import '../../css/x/xlrrn_4li.css';
import '../../css/w/wf3innpgg.css';
import '../../css/f/fwaij5b2p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9uGwD9fx"><g class="aql7dnt-u"><path class="p1r_41bpz"/><path class="xlrrn_4li"/><path class="wf3innpgg"/><path class="fwaij5b2p"/></g></mask></defs><path mask="url(#SVG9uGwD9fx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:peoples-two" /></template>
