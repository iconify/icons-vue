<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/isv_boq8z.css';
import '../../css/h/h9s5--3pf.css';
import '../../css/k/k3a0r8b1f.css';
import '../../css/p/pljx_gb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="isv_boq8z"/><path class="h9s5--3pf"/><path class="k3a0r8b1f"/><path class="pljx_gb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-edit-effects" /></template>
