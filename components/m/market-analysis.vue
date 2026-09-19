<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/e/ej4rzcb4e.css';
import '../../css/p/pa8fw9lpr.css';
import '../../css/k/kbwz4fv-v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhMLTjd1r"><g class="aql7dnt-u"><path class="ej4rzcb4e"/><path class="pa8fw9lpr"/><path class="kbwz4fv-v"/></g></mask></defs><path mask="url(#SVGhMLTjd1r)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:market-analysis" /></template>
