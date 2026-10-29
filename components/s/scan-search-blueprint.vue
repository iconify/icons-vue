<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vq6uo5d_c.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/u/udrcxhb7o.css';
import '../../css/i/iqqttfbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vq6uo5d_c wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="l9lv5_bcf wm-k"/><circle class="udrcxhb7o wm-a"/><path class="iqqttfbhi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-search-blueprint" /></template>
