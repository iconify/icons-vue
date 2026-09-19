<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r14ef2_yx.css';
import '../../css/w/wuut7d5_x.css';
import '../../css/s/s89r_abgl.css';
import '../../css/r/rswqdxahi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdOrh0bGV"><g class="ft5dv1b6b"><path class="r14ef2_yx"/><rect class="wuut7d5_x"/><rect class="s89r_abgl"/><path class="rswqdxahi"/></g></mask></defs><path mask="url(#SVGdOrh0bGV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:projector-one" /></template>
