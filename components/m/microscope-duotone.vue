<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/za7tfj8mb.css';
import '../../css/a/afq4fvbxy.css';
import '../../css/u/u2il3lb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="za7tfj8mb"/><path class="afq4fvbxy"/><path class="u2il3lb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:microscope-duotone" /></template>
