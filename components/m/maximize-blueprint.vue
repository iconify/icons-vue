<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/go1md04ik.css';
import '../../css/b/bxjv56brc.css';
import '../../css/k/kbr-34uax.css';
import '../../css/q/q9crmh73i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="go1md04ik wm-deco"/><path class="bxjv56brc wm-deco"/><path class="kbr-34uax"/><path class="q9crmh73i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-blueprint" /></template>
