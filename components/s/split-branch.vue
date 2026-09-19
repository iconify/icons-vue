<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v_j2mjbpq.css';
import '../../css/i/iiqksgb7d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGphGeOdXM"><g class="ft5dv1b6b"><path class="v_j2mjbpq"/><path class="iiqksgb7d"/></g></mask></defs><path mask="url(#SVGphGeOdXM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:split-branch" /></template>
