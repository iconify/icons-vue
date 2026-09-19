<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/jm8jfs5cr.css';
import '../../css/d/de8dzpspb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmGuvjbTO"><g class="v3_i3wktz"><path class="jm8jfs5cr"/><path class="de8dzpspb"/></g></mask></defs><path mask="url(#SVGmGuvjbTO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:mall-bag" /></template>
