<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/w/wtnpixb-s.css';
import '../../css/x/xff5tx9kz.css';
import '../../css/y/ytdu-x5xr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdLAyjlIH"><g class="v3_i3wktz"><path class="wtnpixb-s"/><path class="xff5tx9kz"/><path class="ytdu-x5xr"/></g></mask></defs><path mask="url(#SVGdLAyjlIH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:treasure-chest" /></template>
