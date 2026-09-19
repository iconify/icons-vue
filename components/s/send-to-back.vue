<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/o76v0vh3i.css';
import '../../css/x/xdmoomhwk.css';
import '../../css/j/jc6ju62gl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVHGVby4n"><g class="v3_i3wktz"><path class="o76v0vh3i"/><path class="xdmoomhwk"/><path class="jc6ju62gl"/></g></mask></defs><path mask="url(#SVGVHGVby4n)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:send-to-back" /></template>
