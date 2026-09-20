<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n4v2kwb_q.css';
import '../../css/i/izo4pibwp.css';
import '../../css/a/au9wb8bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n4v2kwb_q"/><path class="izo4pibwp"/><path class="au9wb8bvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:performance-increase-clipboard" /></template>
