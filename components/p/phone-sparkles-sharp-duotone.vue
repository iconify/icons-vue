<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vk9v_xb8o.css';
import '../../css/s/snibgdcaa.css';
import '../../css/n/n19x7nf9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vk9v_xb8o"/><path class="snibgdcaa"/><path class="n19x7nf9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-sparkles-sharp-duotone" /></template>
