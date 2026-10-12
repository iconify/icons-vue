<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hoqmwc11w.css';
import '../../css/n/nb9d1ibpa.css';
import '../../css/f/fseys5djj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hoqmwc11w"/><path class="nb9d1ibpa"/><path class="fseys5djj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:octagon-x-duotone" /></template>
