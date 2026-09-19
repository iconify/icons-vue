<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpdq4hb-m.css';
import '../../css/l/l0r8j72es.css';
import '../../css/m/m40vt8b2k.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGX6GfSdon"><g class="lpdq4hb-m"><path class="l0r8j72es"/><path class="m40vt8b2k"/></g></mask></defs><path mask="url(#SVGX6GfSdon)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:xigua" /></template>
