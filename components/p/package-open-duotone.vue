<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qz1zm2bdm.css';
import '../../css/i/iidqvbcem.css';
import '../../css/w/wk97p5bdt.css';
import '../../css/b/b9k9m9mqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qz1zm2bdm"/><path class="iidqvbcem"/><path class="wk97p5bdt"/><path class="b9k9m9mqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-open-duotone" /></template>
