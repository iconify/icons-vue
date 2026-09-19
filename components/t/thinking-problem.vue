<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h6karfbzd.css';
import '../../css/r/rs6xfdeqy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGP2l5AdEm"><g class="aql7dnt-u"><path class="h6karfbzd"/><path class="rs6xfdeqy"/></g></mask></defs><path mask="url(#SVGP2l5AdEm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:thinking-problem" /></template>
