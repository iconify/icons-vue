<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywk57vfom.css';
import '../../css/p/py2rm2fdy.css';
import '../../css/u/u5l_fgbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":258,"height":199};
const content = `<path clip-rule="evenodd" class="ywk57vfom"/><path class="py2rm2fdy"/><path clip-rule="evenodd" class="u5l_fgbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:t3-stack-light" /></template>
