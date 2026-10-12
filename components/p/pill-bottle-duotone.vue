<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n3ttj5l_c.css';
import '../../css/i/imq2kdb-v.css';
import '../../css/l/lmjattb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n3ttj5l_c"/><path class="imq2kdb-v"/><path class="lmjattb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pill-bottle-duotone" /></template>
