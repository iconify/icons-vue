<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tvi4lgpob.css';
import '../../css/b/b4jr9vbne.css';
import '../../css/d/daz97mqlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tvi4lgpob"/><path class="b4jr9vbne"/><path class="daz97mqlm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:satellite-duotone" /></template>
