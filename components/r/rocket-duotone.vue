<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mzt6m_f5h.css';
import '../../css/d/de9j4cbpo.css';
import '../../css/o/o-6jqq_fb.css';
import '../../css/i/ifpajzgpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mzt6m_f5h"/><path class="de9j4cbpo"/><path class="o-6jqq_fb"/><path class="ifpajzgpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rocket-duotone" /></template>
