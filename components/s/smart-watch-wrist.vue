<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ae85lnhzi.css';
import '../../css/w/wzpm1injt.css';
import '../../css/b/bzgxe9e7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ae85lnhzi"/><path class="wzpm1injt"/><path class="bzgxe9e7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:smart-watch-wrist" /></template>
