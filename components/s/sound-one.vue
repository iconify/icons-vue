<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uh769acwe.css';
import '../../css/e/eevc8fboi.css';
import '../../css/g/gootj1b_k.css';
import '../../css/p/pxyeaeueo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8aqG1cma"><g class="ft5dv1b6b"><path class="uh769acwe"/><path class="eevc8fboi"/><rect class="gootj1b_k"/><path class="pxyeaeueo"/></g></mask></defs><path mask="url(#SVG8aqG1cma)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sound-one" /></template>
