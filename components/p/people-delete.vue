<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kznc4_ijf.css';
import '../../css/f/fvx1854ux.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdHQ1QFib"><g class="v3_i3wktz"><path class="kznc4_ijf"/><path class="fvx1854ux"/></g></mask></defs><path mask="url(#SVGdHQ1QFib)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people-delete" /></template>
