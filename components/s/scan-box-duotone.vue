<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/syqhj5bsw.css';
import '../../css/e/eoiplfbya.css';
import '../../css/s/s2pgtxb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="syqhj5bsw"/><path class="eoiplfbya"/><path class="s2pgtxb9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-box-duotone" /></template>
