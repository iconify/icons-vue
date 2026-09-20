<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvtop1btw.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/ws5p-pbkd.css';
import '../../css/a/a7hvicdlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVG01JF36rt" class="lvtop1btw"/></defs><g class="ft5dv1b6b"><use href="#SVG01JF36rt"/><use href="#SVG01JF36rt"/><path class="ws5p-pbkd"/><path class="a7hvicdlr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:module-flat" /></template>
