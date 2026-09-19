<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iuj1n4p2e.css';
import '../../css/m/m9v8-3bwm.css';
import '../../css/r/r7eam_5zr.css';
import '../../css/v/vaxiz94qp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJNybLe6r"><g class="ft5dv1b6b"><path class="iuj1n4p2e"/><path class="m9v8-3bwm"/><rect class="r7eam_5zr"/><path class="vaxiz94qp"/></g></mask></defs><path mask="url(#SVGJNybLe6r)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sound-one" /></template>
