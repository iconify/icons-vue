<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mb3gk9bpt.css';
import '../../css/k/km9xy360q.css';
import '../../css/g/gmcl-ec6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mb3gk9bpt"/><path class="km9xy360q"/><path class="gmcl-ec6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sun-dim-duotone" /></template>
