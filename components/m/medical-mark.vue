<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bep--83gd.css';
import '../../css/u/uo1wgac5o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG970hQeuX"><g class="v3_i3wktz"><path class="bep--83gd"/><path class="uo1wgac5o"/></g></mask></defs><path mask="url(#SVG970hQeuX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:medical-mark" /></template>
