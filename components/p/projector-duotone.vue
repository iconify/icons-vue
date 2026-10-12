<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/datywxy9g.css';
import '../../css/w/w9w52560n.css';
import '../../css/b/b0igw0mrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="datywxy9g"/><path class="w9w52560n"/><path class="b0igw0mrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:projector-duotone" /></template>
