<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j51dv817o.css';
import '../../css/v/v37v3sbeg.css';
import '../../css/d/dfqrkobme.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkZkHfbIA"><g class="ft5dv1b6b"><path class="j51dv817o"/><path class="v37v3sbeg"/><path class="dfqrkobme"/></g></mask></defs><path mask="url(#SVGkZkHfbIA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:strongbox" /></template>
