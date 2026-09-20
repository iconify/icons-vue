<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r6knjfq9q.css';
import '../../css/f/fxwmdgbgf.css';
import '../../css/k/kd35jjh2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r6knjfq9q"/><path class="fxwmdgbgf"/><path class="kd35jjh2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:safety-exit-door" /></template>
