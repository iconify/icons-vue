<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgga7abld.css';
import '../../css/y/yplbaw3db.css';
import '../../css/j/jkcu7kbhq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiGiSwbSe"><g class="cgga7abld"><path class="yplbaw3db"/><path class="jkcu7kbhq"/></g></mask></defs><path mask="url(#SVGiGiSwbSe)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rowing" /></template>
