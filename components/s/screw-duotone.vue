<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tkb1vr54i.css';
import '../../css/h/h88dnnzlp.css';
import '../../css/x/xa703b19s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tkb1vr54i"/><path class="h88dnnzlp"/><path class="xa703b19s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:screw-duotone" /></template>
