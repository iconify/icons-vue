<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/l/lmrd5-bhw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJHJ5gc3O"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="lmrd5-bhw"/></g></mask></defs><path mask="url(#SVGJHJ5gc3O)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:winking-face" /></template>
