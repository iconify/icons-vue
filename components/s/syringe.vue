<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r042qtb1w.css';
import '../../css/k/k_2k-fkox.css';
import '../../css/h/h7btmc92c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r042qtb1w"/><path class="k_2k-fkox"/><path class="h7btmc92c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:syringe" /></template>
