<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/be7lcnw4z.css';
import '../../css/m/mo_--sb_d.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/u/umn_serzn.css';
import '../../css/e/e8qdm7btf.css';
import '../../css/f/fgvr94b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="be7lcnw4z wm-deco"/><path class="mo_--sb_d wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="umn_serzn wm-k"/><path class="e8qdm7btf wm-s"/><path class="fgvr94b2i wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-dot-blueprint" /></template>
