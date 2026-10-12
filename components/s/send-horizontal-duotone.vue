<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dy_c4nbmc.css';
import '../../css/e/elhn0g7ph.css';
import '../../css/f/f6qv5_awe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dy_c4nbmc"/><path class="elhn0g7ph"/><path class="f6qv5_awe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:send-horizontal-duotone" /></template>
