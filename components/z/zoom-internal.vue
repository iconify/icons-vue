<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wkaq4nb8y.css';
import '../../css/c/c6ej-2d7p.css';
import '../../css/n/nv5b4pbqz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGo9psSdWd"><g class="ufeehvblu"><path class="wkaq4nb8y"/><path class="c6ej-2d7p"/><path class="nv5b4pbqz"/></g></mask></defs><path mask="url(#SVGo9psSdWd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:zoom-internal" /></template>
