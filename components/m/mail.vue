<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/ctq6evbba.css';
import '../../css/l/lh_zh7biy.css';
import '../../css/f/fri595bxy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGl0YEsefU"><g class="ufeehvblu"><path class="ctq6evbba"/><path class="lh_zh7biy"/><path class="fri595bxy"/></g></mask></defs><path mask="url(#SVGl0YEsefU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:mail" /></template>
