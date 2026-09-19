<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nvxkylbdg.css';
import '../../css/y/yyx_3z7mv.css';
import '../../css/c/c6nrszujt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuSC5DboZ"><g class="v3_i3wktz"><path class="nvxkylbdg"/><path clip-rule="evenodd" class="yyx_3z7mv"/><path class="c6nrszujt"/></g></mask></defs><path mask="url(#SVGuSC5DboZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:open-door" /></template>
