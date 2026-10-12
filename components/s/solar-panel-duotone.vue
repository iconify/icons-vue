<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b586-pbxl.css';
import '../../css/k/kkpssnb2s.css';
import '../../css/f/fnw9pc43f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b586-pbxl"/><path class="kkpssnb2s"/><path class="fnw9pc43f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:solar-panel-duotone" /></template>
