<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/n5fnjzvzx.css';
import '../../css/d/d843ssbel.css';
import '../../css/e/e6g-47-tx.css';
import '../../css/j/j79vh-b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="n5fnjzvzx wm-deco"/><path class="d843ssbel wm-deco"/><path class="e6g-47-tx wm-k"/><path class="j79vh-b8k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rabbit-blueprint" /></template>
