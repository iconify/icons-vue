<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/v/v_02abb1o.css';
import '../../css/t/twg4s5urk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGo6IM2cJW"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="v_02abb1o"/><circle class="twg4s5urk"/></g></mask></defs><path mask="url(#SVGo6IM2cJW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:winking-face-with-open-eyes" /></template>
