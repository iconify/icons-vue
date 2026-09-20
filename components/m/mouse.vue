<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gbsbs-cqo.css';
import '../../css/n/nui9lsblr.css';
import '../../css/r/ri4no1frt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gbsbs-cqo"/><path class="nui9lsblr"/><path class="ri4no1frt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:mouse" /></template>
