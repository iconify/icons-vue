<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/rsqaxjbon.css';
import '../../css/x/x2opukbfv.css';
import '../../css/v/vds6lqbpe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEryUvHPo"><g class="v3_i3wktz"><path class="rsqaxjbon"/><path class="x2opukbfv"/><path class="vds6lqbpe"/></g></mask></defs><path mask="url(#SVGEryUvHPo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:stack-light" /></template>
