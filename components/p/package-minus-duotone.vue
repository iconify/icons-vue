<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/is1q88b4t.css';
import '../../css/l/l7ocqgb5a.css';
import '../../css/b/bmlydqbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="is1q88b4t"/><path class="l7ocqgb5a"/><path class="bmlydqbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-minus-duotone" /></template>
