<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rp-frbc_i.css';
import '../../css/b/bk0dwpbms.css';
import '../../css/u/ue-rx-bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rp-frbc_i"/><path class="bk0dwpbms"/><path class="ue-rx-bbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:smartphone-user-round-duotone" /></template>
