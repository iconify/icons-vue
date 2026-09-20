<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tdzzo8b5j.css';
import '../../css/z/zyvddlb3n.css';
import '../../css/r/rum9obbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tdzzo8b5j"/><path class="zyvddlb3n"/><path class="rum9obbsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-bag-sad" /></template>
