<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/dmdf19b6r.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/i/igsc02sfs.css';
import '../../css/m/mpivlabzb.css';
import '../../css/p/p4wcr408t.css';
import '../../css/b/bdz19jyxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="dmdf19b6r wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="igsc02sfs wm-k"/><path class="mpivlabzb wm-a"/><path class="p4wcr408t wm-k"/><path class="bdz19jyxt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:repeat-blueprint" /></template>
