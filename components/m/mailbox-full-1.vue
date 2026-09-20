<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l1nnh9gpj.css';
import '../../css/q/qt5di4bqt.css';
import '../../css/h/hfvj0jbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l1nnh9gpj"/><path class="qt5di4bqt"/><path class="hfvj0jbyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:mailbox-full-1" /></template>
