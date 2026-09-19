<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/p/pzosztbse.css';
import '../../css/h/hkuwvwbvi.css';
import '../../css/y/ylhp4cc8g.css';
import '../../css/s/sj6rcj4hn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGV81Qidve"><g class="aql7dnt-u"><path class="pzosztbse"/><path class="hkuwvwbvi"/><path class="ylhp4cc8g"/><path class="sj6rcj4hn"/></g></mask></defs><path mask="url(#SVGV81Qidve)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:peoples" /></template>
