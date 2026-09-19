<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vl0sbknne.css';
import '../../css/i/ir6ml4blk.css';
import '../../css/a/anbnfobac.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVlQBebkA"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="vl0sbknne"/><path class="ir6ml4blk"/><path clip-rule="evenodd" class="anbnfobac"/></g></mask></defs><path mask="url(#SVGVlQBebkA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:painted-eggshell" /></template>
