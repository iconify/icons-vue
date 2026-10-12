<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dhbt0bbiv.css';
import '../../css/v/v5ygwybkd.css';
import '../../css/r/r_iishbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dhbt0bbiv"/><path class="v5ygwybkd"/><path class="r_iishbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tablets-duotone" /></template>
