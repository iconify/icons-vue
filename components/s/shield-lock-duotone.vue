<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/suve9jbyr.css';
import '../../css/v/vu6xhtzyn.css';
import '../../css/s/sa9op7ect.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="suve9jbyr"/><path class="vu6xhtzyn"/><path class="sa9op7ect"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-lock-duotone" /></template>
