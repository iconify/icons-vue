<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qdbr9_1py.css';
import '../../css/v/vh156zb_f.css';
import '../../css/a/au67ybcgw.css';
import '../../css/v/v-y43hbiv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpJGKkeEd"><g class="v3_i3wktz"><path class="qdbr9_1py"/><path class="vh156zb_f"/><path class="au67ybcgw"/><path class="v-y43hbiv"/></g></mask></defs><path mask="url(#SVGpJGKkeEd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:user-to-user-transmission" /></template>
