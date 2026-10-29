<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vn3pz2urw.css';
import '../../css/l/lwtndu7mg.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/y/yaeqedwkp.css';
import '../../css/b/bjhx8wydq.css';
import '../../css/r/riz3aabkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vn3pz2urw wm-deco"/><path class="lwtndu7mg wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="wm-k yaeqedwkp"/><path class="bjhx8wydq wm-a"/><path class="riz3aabkw wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stroller-blueprint" /></template>
