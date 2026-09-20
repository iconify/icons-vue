<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xxoqyms1v.css';
import '../../css/y/ycpresbqn.css';
import '../../css/c/cebpj_b9y.css';
import '../../css/s/s5ir6dwik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xxoqyms1v"/><path class="ycpresbqn"/><path class="cebpj_b9y"/><path class="s5ir6dwik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:notes-add" /></template>
