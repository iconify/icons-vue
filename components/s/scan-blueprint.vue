<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/s_ljr6bug.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/v/vkn5_ac_i.css';
import '../../css/m/mvlqq2b6g.css';
import '../../css/l/lvenwvbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="s_ljr6bug wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="vkn5_ac_i wm-k"/><path class="mvlqq2b6g wm-a"/><path class="lvenwvbyo wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-blueprint" /></template>
