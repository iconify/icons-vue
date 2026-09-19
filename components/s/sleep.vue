<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/k0_khzzsi.css';
import '../../css/k/kvnld0b2g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmxNVWcwA"><g class="v3_i3wktz"><path class="k0_khzzsi"/><path class="kvnld0b2g"/></g></mask></defs><path mask="url(#SVGmxNVWcwA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sleep" /></template>
