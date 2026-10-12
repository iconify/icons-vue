<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qc8tt5qhn.css';
import '../../css/b/bc3q-7bmw.css';
import '../../css/k/kabxu5bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qc8tt5qhn"/><path class="bc3q-7bmw"/><path class="kabxu5bjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pickaxe-duotone" /></template>
