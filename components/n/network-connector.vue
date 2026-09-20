<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pdj3gvbnp.css';
import '../../css/m/mys4ucbkk.css';
import '../../css/a/ajmr8884e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pdj3gvbnp"/><path class="mys4ucbkk"/><path class="ajmr8884e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:network-connector" /></template>
