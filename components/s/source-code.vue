<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c9lqn04fy.css';
import '../../css/e/e9to63mfe.css';
import '../../css/f/f0cnj6bkn.css';
import '../../css/k/k1uq304yb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuERJkd4M"><g class="ft5dv1b6b"><path class="c9lqn04fy"/><path class="e9to63mfe"/><path class="f0cnj6bkn"/><circle transform="matrix(0 -1 -1 0 10 14)" class="k1uq304yb"/><circle transform="matrix(0 -1 -1 0 16 14)" class="k1uq304yb"/></g></mask></defs><path mask="url(#SVGuERJkd4M)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:source-code" /></template>
