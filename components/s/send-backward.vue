<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/ynqx2zfnc.css';
import '../../css/o/odhm74bfl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGd09YJeLr"><g class="v3_i3wktz"><path class="ynqx2zfnc"/><path class="odhm74bfl"/></g></mask></defs><path mask="url(#SVGd09YJeLr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:send-backward" /></template>
