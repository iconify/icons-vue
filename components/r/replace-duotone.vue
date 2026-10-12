<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/ptfbq5b_s.css';
import '../../css/k/kh5f1ub7k.css';
import '../../css/x/x00sututu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ptfbq5b_s"/><path class="kh5f1ub7k"/><path class="x00sututu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:replace-duotone" /></template>
