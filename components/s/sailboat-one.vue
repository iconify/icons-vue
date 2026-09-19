<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/n22bo8byq.css';
import '../../css/a/ab1wfbc-v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJv0Ade4j"><g class="v3_i3wktz"><path class="n22bo8byq"/><path class="ab1wfbc-v"/></g></mask></defs><path mask="url(#SVGJv0Ade4j)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sailboat-one" /></template>
